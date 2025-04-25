# Executable Environment for OSF Project [tgf3q](https://osf.io/tgf3q/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** The Late Gravettian Site of Kostënki 21 Layer III, Russia: a Chronocultural Reassessment Based on a New Interpretation of the Significance of Intra-site Spatial Patterning

**Project Description:**
> Postprint and SI for paper Reynolds, N., Germonpré, M., Bessudnov, A. A. and Sablin, M. V. (2019) The Late Gravettian Site of Kostënki 21 Layer III, Russia: a Chronocultural Reassessment Based on a New Interpretation of the Significance of Intra-site Spatial Patterning. Journal of Paleolithic Archaeology 2 (2): 160–210. https://doi.org/10.1007/s41982-018-0018-6

These files contain descriptive data and metadata for Anosovka points and shouldered points from the Upper Palaeolithic sites of Kostënki 21/III, Kostënki 11/II and Gagarino (Russia) and R code used in the paper.

**Original OSF Page:** [https://osf.io/tgf3q/](https://osf.io/tgf3q/)

---

**Important Note:** The contents of the `tgf3q_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_tgf3q/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_tgf3q/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `tgf3q_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-tgf3q:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-tgf3q
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
