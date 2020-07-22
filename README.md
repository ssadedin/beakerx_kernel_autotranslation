<!--
    Copyright 2020 TWO SIGMA OPEN SOURCE, LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->

<img width="900" alt="banner" src="https://user-images.githubusercontent.com/963093/34594978-31d70312-f1a2-11e7-861c-705a9e932c3c.png">

# BeakerX: Beaker extensions for Jupyter - Autotranslation

BeakerX is a collection of JVM kernels and interactive widgets for
plotting, tables, autotranslation, and other extensions to Jupyter
Notebook.

This repository contains BeakerX Autotranslation components.

Please check the main repositoy for further informations:
[beakerx](https://github.com/twosigma/beakerx)


### Conda Install (linux and mac)

```
conda env create -n beakerx_atotranslation -f configuration.yml
conda activate beakerx_atotranslation # For conda versions prior to 4.6, run: source activate beakerx
(pip install -r requirements.txt --verbose)
beakerx_kernel_autotranslation install
```

