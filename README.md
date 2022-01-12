# CSM-PEGN552 Course Template

Click the button below to launch a notebook sample
[![Binder](https://img.shields.io/static/v1.svg?logo=Jupyter&label=launch&message=Binder%0A%2B%0AAVEVA_DataHub&color=3d1152)](https://ovh.mybinder.org/v2/gh/academic-hub/notebooks-env/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Facademic-hub%252FCSM-PEGN552%26urlpath%3Dtree%252FCSM-PEGN552%252F%26branch%3Dmain)

## Instructions for TAs

### Overview

This repository (https://github.com/academic-hub/CSM-PEGN552) is a class notebook template to seed other repositories you can then modify at will. 

In summary it contains:

* one exercise notebook using the [Wind Farms dataset](https://academic.osisoft.com/datasets)
* one markdown document with the assignment
* a common project description 
* save and restore notebook instructions within Binder

Below are the steps and details how to publish your own repository

### Class publication steps

Prerequisites:
* a Github account 
* an Academic Hub account for data accesses (register at https://academic.osisoft.com/register)

We recommend [Github desktop](https://desktop.github.com/) for dealing with Github repository. **The steps below assumes it is already installed on your laptop.**

1. Go to https://github.com/academic-hub/CSM-PEGN552 and click the "Use this template" button:<br>![](https://academichub.blob.core.windows.net/hub/binder/hub-ta-binder-step1.png)<br><br>
2. Fill in the information as indicated below to create a new repository:<br>![](https://academichub.blob.core.windows.net/hub/binder/hub-ta-binder-step2.png)<br><br>
3. Clone the repository on your laptop with the simple step shown below:<br>![](https://academichub.blob.core.windows.net/hub/binder/hub-ta-binder-step3.png)<br><br>
4. Modify the content for the class as needed. Note that an installation of [Anaconda](https://repo.anaconda.com/archive/Anaconda3-5.3.1-Windows-x86_64.exe) is required to modify and run the notebook 
5. Once the repository on Github is ready for publication, go to https://github.com/academic-hub/notebooks-env#link-generator-for-binder-based-classes and follow the steps to build a link to the class repo:<br>![](https://academichub.blob.core.windows.net/hub/binder/hub-ta-binder-link-gen.png)<br><br>
5. Add the following markdown to the README.md of the class repo, replace `<step-4-link>` by the generated URL from Step 4:

```
    [![Binder](https://img.shields.io/static/v1.svg?logo=Jupyter&label=launch&message=Binder%0A%2B%0AAVEVA_DataHub&color=3d1152)](<step-4-link)
```

Your Github class repository is now ready to be shared with students, just distribute its URL. 

No Github account is necessary to run notebooks. **But data accesses do require an AVEVA Academic Hub account for each student. Please go to https://academic.osisoft.com/new-class for details.**


