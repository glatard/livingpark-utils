# LivingPark utils

A collection of utility functions to write LivingPark notebooks.

Usage examples:

```
import livingpark_utils

utils = livingpark_utils.LivingParkUtils('scherfler-etal')
utils.notebook_init()
utils.download_ppmi_metadata(['Demographics.csv'])
utils.find_nifti_file_in_cache(x['PATNO'], x['EVENT_ID'], x['Description'])
utils.disease_duration()
utils.moca2mmse(2)
```

## Contributing guidelines

We welcome contributions of any kind in the form of Pull-Request to this repository.
See also [LivingPark contributing guidelines](https://github.com/LivingPark-MRI/documentation).


Make sure to:
* Use Python type annotations
* Include Python docstrings for all functions
* Format docstrings 
* Run `psf/black` on the files you modify
* Run `pre-commit run --all` before committing, this will be checked in your PR
