## Impedora

Free PCB signal-integrity calculators that run in your browser, at **[impedora.com](https://impedora.com)**. No install, no account, nothing uploaded.

- **[Trace](https://impedora.com/trace/)**: impedance, delay and loss of microstrip, stripline and differential pairs, from a 2D field solver.
- **[Via](https://impedora.com/via/)**: S-parameters of a via with its pads, antipads, stitching vias, trace launch, stub, backdrill or blind depth, single-ended or differential, with a Touchstone download.
- **[Current](https://impedora.com/current/)**: trace width for a current and temperature rise (IPC-2221).
- **[Stackup](https://impedora.com/stackup/)**: describe the board once, or import it from KiCad.

### Checked in the open

The via model is not a 3D solver. It is a fast physics-based model, compared with a 3D finite-element solver (Palace) on twenty-five cases up to 50 GHz. The trace solver is compared with exact solutions and an independent finite-element solver. Every case, the 3D pipeline and the stored results are in **[impedora/validation](https://github.com/impedora/validation)**, so anyone can rerun them. The results are on the site's [Validation](https://impedora.com/validation/) page.

### Help make it right

- **A result looks wrong?** Open an issue on [impedora/validation](https://github.com/impedora/validation/issues) with your inputs, the value you expected and where it comes from.
- **Have measured S-parameters or a 3D simulation of a via or trace?** That is the most useful thing you can add. See [how to contribute data](https://github.com/impedora/validation/blob/main/CONTRIBUTING.md).
- Anything else: [contact@impedora.com](mailto:contact@impedora.com).
