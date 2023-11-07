# Learning Through Target Bursts (LTTB)

This is the accompanying source code of the paper: "*Beyond spiking networks: The computational advantages of dendritic amplification and input segregation*", [PNAS, Vol. 120 (2023) e2220743120](https://doi.org/10.1073/pnas.2220743120), by Cristiano Capone<sup>\*</sup>, Cosimo Lupo<sup>\*</sup>, Paolo Muratore, Pier Stanislao Paolucci.

Please give credit to this paper if you use or modify the code in a derivative work. This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

The code is written in Python and organized as follows. The network model itself is defined into the `lttb.py` module (which defines the `LTTB` model object). The model parameters used for the different experiments are organized in different sections of a unique `json` configuration file.

To easily replicate the experiments presented in the paper we provide Jupyter Notebooks that can be run on their own.

## External Dependencies
To run the different experiments the following external libraries should be installed on the machine:

```python
jupyter notebook    # for an easier user interface
numpy               # Basic numerical array library
matplotlib          # Used for producing the various visualizations
json                # Use to parse the model configuration file
tqdm
```

## Bursts & Context Switch

To reproduce the results presented in `Figure 3` and `Figure 4` of the paper, simply run the associated notebooks: `Figure_3.ipynb` and `Figure_4.ipynb`.

## Button & Food Task

To reproduce the results presented in `Figure 5` of the paper, run the associated notebook `Figure_5.ipynb`.

To reproduce the results presented in `Figure 6` of the paper, for the spiking network, run the associated notebook `Figure_6.ipynb`, in the LTTS folder.
