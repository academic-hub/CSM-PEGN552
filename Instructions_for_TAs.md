# Instructions for TAs

## Overview

Here are the steps to customize and publish Academic Hub based material for a class (we recommend [GitHub Desktop](https://desktop.github.com/) for interactions with Github repos):

1. Fork the current Github repository (NOTE: at this point your new repo is public)
2. Modify/add content to your forked repo as needed before sharing with students
3. [TODO: STEPS HOW TO CLONE/COPY INTO CLASS REPO]
4. Go to https://github.com/academic-hub/notebooks-env and follow the steps to build a link to the class repo
5. Add the following markdown to the README.md of the class repo, replace <step-4-link> by the generated URL from Step 4:

```
    [![Binder](https://img.shields.io/static/v1.svg?logo=Jupyter&label=launch&message=Binder%0A%2B%0AAVEVA_DataHub&color=3d1152)](<step-4-link)
```

Your Github class repository is now ready to be shared with students, just distribute its URL. 

No Github account is necessary to run notebooks. **But data accesses do require an AVEVA Academic Hub account for each student. Please go to https://academic.osisoft.com for details.**

NOTE: Binder, the free service to run notebooks for students, requires that the Github repository must be public.  