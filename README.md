<!--readme-start-->

# DataJoint Elements for Neurophysiology

![Logo](docs/img/elements-logo.png)

DataJoint Elements provides an efficient approach for neuroscience labs
to create and manage _scientific data workflows_: the complex multi-step methods
for data collection, preparation, processing, analysis, and modeling that
researchers must perform in the course of an experimental study. The work is
derived from the developments in leading neuroscience projects and uses the
[DataJoint framework](https://datajoint.org) for defining, deploying, and
sharing their data workflows.

**_DataJoint_**

> the open-source framework for data pipelines and automated computational
> workflows + related documentation, tools, and utilities.

**_DataJoint Elements_**

> a collection of curated modules for assembling workflows for the major
> modalities of neurophysiology experiments + related documentation, tools, and
> utilities.

An overview of the principles of DataJoint workflows and the goals of DataJoint
Elements are described in the position paper
["DataJoint Elements: Data Workflows for Neurophysiology"](https://www.biorxiv.org/content/10.1101/2021.03.30.437358v2).

# Project Structure

- [Management and Policies](docs/management/plan.md)
- [Design Principles](docs/usage/design-principles.md)
- [Guidelines for Adoption](docs/usage/adopt.md)
- [Glossary](docs/usage/glossary.md)

## DataJoint Elements

| DataJoint Element                                                                                     | Example workflow                                                                                                                                                                     | Background, Features, and Status                   | Tutorial Video                                      |
| :----------------------------------------------------------------------------------------             | :-----------------------------------------------------------------------------------                                                                                                 | :---------------------------------------------     | :-------------                                      |
| [Lab management](https://github.com/datajoint/element-lab)                                            | See Session                                                                                                                                                                          | [Link](docs/description/lab.md)                    | See Session                                         |
| [Animal management](https://github.com/datajoint/element-animal)                                      | See Session                                                                                                                                                                          | [Link](docs/description/animal.md)                 | See Session                                         |
| [Experiment Session management](https://github.com/datajoint/element-session)                         | [Lab, subject and session management](https://github.com/datajoint/workflow-session)                                                                                                 | [Link](docs/description/session.md)                | [Link](https://www.youtube.com/watch?v=NRqpKNoHEY0) |
| [Extracellular array electrophysiology](https://github.com/datajoint/element-array-ephys)             | [Neuropixels](https://github.com/datajoint/workflow-array-ephys)                                                                                                                     | [Link](docs/description/array_ephys.md)            | [Link](https://youtu.be/KQlGYOBq7ow?t=3590)         |
| [Calcium imaging](https://github.com/datajoint/element-calcium-imaging)                               | [Multiphoton laser scanning](https://github.com/datajoint/workflow-calcium-imaging)                                                                                                  | [Link](docs/description/calcium_imaging.md)        | [Link](https://www.youtube.com/watch?v=gFLn0GB1L30) |
| [Miniscope imaging](https://github.com/datajoint/element-miniscope)                                   | [UCLA Miniscope](https://github.com/datajoint/workflow-miniscope)                                                                                                                    | [Link](docs/description/miniscope.md)              | [Link](https://www.youtube.com/watch?v=nWUcPFZOSVw) |
| [DeepLabCut](https://github.com/datajoint/element-deeplabcut)                                         | [Workflow for pose tracking](https://github.com/datajoint/workflow-deeplabcut)                                                                                                       | [Link](docs/description/deeplabcut.md)             | [Link](https://www.youtube.com/watch?v=8FDjTuQ52gQ) |
| [Event- and trial-based experiments](https://github.com/datajoint/element-event)                      | [Workflow for Neuropixels](https://github.com/datajoint/workflow-array-ephys) <br/> [Workflow for multiphoton laser scanning](https://github.com/datajoint/workflow-calcium-imaging) | [Link](docs/description/event.md)                  | [Link](https://www.youtube.com/watch?v=DLYqnj40eAM) |
| [Electrode localization for Neuropixels](https://github.com/datajoint/element-electrode-localization) | [Workflow for Neuropixels](https://github.com/datajoint/workflow-array-ephys)                                                                                                        | [Link](docs/description/electrode_localization.md) | [Link](https://www.youtube.com/watch?v=YRXokFHkLGg) |
| [Facemap](https://github.com/datajoint/element-facemap)                                               |                                                                                                                                                                                      | [Link](docs/description/facemap.md)                |                                                     |
| [Visual Stimulation](https://github.com/datajoint/element-visual-stimulus/)                           |                                                                                             | [Link](docs/description/visual_stimulus.md)        | [Link](https://www.youtube.com/watch?v=dtEggZX9Fw4) |

## DataJoint framework

- [DataJoint for Python](https://github.com/datajoint/datajoint-python)
- [DataJoint for MATLAB](https://github.com/datajoint/datajoint-matlab)
- [DataJoint Documentation](https://docs.datajoint.org)
- [DataJoint Tutorials](https://tutorials.datajoint.io)
- [Docker image for MySQL server configured for use with DataJoint](https://github.com/datajoint/mysql-docker)

## DataJoint Interfaces

- [Pharus](https://github.com/datajoint/pharus) — a REST API for interacting
  with DataJoint databases
- [DataJoint LabBook](https://github.com/datajoint/datajoint-labbook) — a
  front-end web interface for viewing and entering data
- [DataJoint SciViz](https://github.com/datajoint/sci-viz) — a low-code
  framework for building websites for interactive data visualizaion.

## DataJoint Online Training

- [DataJoint CodeBook](https://codebook.datajoint.io) — interactive online tutorials

## Feedback

DataJoint and DataJoint Elements are supported by NIH grant U24 NS116470 for disseminating open-source software for neuroscience research. Your feedback is essential for continued funding. Your feedback also helps shape the technology development roadmap for the DataJoint ecosystem. Please tell us about your projects by filling out the [DataJoint Census](https://community.datajoint.io).

## Citation

+ If your work uses DataJoint and DataJoint Elements, please cite the respective Research Resource Identifiers (RRIDs) and manuscripts.

**_DataJoint for Python or MATLAB_**

> Yatsenko D, Reimer J, Ecker AS, Walker EY, Sinz F, Berens P, Hoenselaar A, Cotton RJ,
> Siapas AS, Tolias AS. DataJoint: managing big scientific data using MATLAB or Python.
> bioRxiv. 2015 Jan 1:031658. doi: https://doi.org/10.1101/031658

<br>

> DataJoint ([RRID:SCR_014543](https://scicrunch.org/resolver/SCR_014543)) - 
> DataJoint for `<Select Python or MATLAB>` (version `<Enter version number>`)

**_DataJoint Elements_**

> Yatsenko D, Nguyen T, Shen S, Gunalan K, Turner CA, Guzman R, Sasaki M, Sitonic D,
> Reimer J, Walker EY, Tolias AS. DataJoint Elements: Data Workflows for
> Neurophysiology. bioRxiv. 2021 Jan 1. doi: https://doi.org/10.1101/2021.03.30.437358

<br>

> DataJoint Elements ([RRID:SCR_021894](https://scicrunch.org/resolver/SCR_021894)) - 
> Element `Enter Element name` (version `<Enter version number>`)

<!--readme-end-->
