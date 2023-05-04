---
layout: page
title: Dancing sychrony and synergy
permalink: /dancing
---

# Project Information

## Data

### Naming Conventions

All data files related to the project should match the following naming convention:

`<what>[_<pair-id>][_<condition>][_<subject-id>][_<additional-information].<file-extension>`.

The following table describes the different parts of the naming convention:

| Part | Description | Applies To | Example |
|------|-------------|---------|---------|
| `<what>` | What the file contains (Required). | all | either: `mocap` captured data, `questionnaire` for questionnaires, `ratingcont` subject continuous ratings, `rating` subject ratings |
| `<pair-id>` | The pair id. This is the subject IDs together. | ratings, mocap | `L1F1` |
| `<condition>` | The condition of the data. | ratings, mocap | `...` |
| `<subject-id>` | The subject id, consisting of role: `L` for leader, `F` for follower, and a numeric ID. | general questionnaires, continuous ratings, subject ratings | `L1`, `F1` |
| `<additional-information>` | Any additional information, including suffixes added by QTM, etc | all | `...` |
| `<file-extension>` | The file extension. | all | `csv`, `xlsx`, `tsv`, `txt`, etc. |

#### Examples

- `mocap_L1F1_cond.csv`: Mocap data for the subjects `L1` and `F1`, where the leader is Leader 1 and the follower is Follower 1
- `ratingcont_L1F1_cond_F1.csv`: Continuous ratings for the subjects `L1` and `F1`, where the rater is Follower 1 and the leader is Leader 1 and the follower is Follower 1
- `questionnaire_L1F1_cond_L1.csv`: Questionnaire data for the subjects `L1` and `F1`, with answers from Leader 1 and the leader is Leader 1 and the follower is Follower 1
- `questionnaire_F1.csv`: General questionnaire data for the subject `F1`, with answers from Follower 1



### Directory Structure

All the data for the project is primarily stored in the `Dancing Coordination - Waade` UCloud Project, in the `Data storage and analysis`.
#### General

The directory structure is described in the following table:

| Directory | Description |
|-----------|-------------|
| `Data storage and analysis/` | The root directory for the data and project related materials. |
| `Data storage and analysis/code/` | Code used in the project. See also: [https://github.com/au-imclab-git/dance_project](https://github.com/au-imclab-git/dance_project) |
| `Data storage and analysis/data/` | Folders per study (e.g. `lindy_full`, `lindy_pilot`). |
| `Data storage and analysis/resources/` | Non-data resources used in the project, e.g. consent form templates, and other documentation. |

#### Data

The data directory structure for all studies in the `Data storage and analysis/data/` folder should match the following:

- `<study_name>`: currently there are `lindy_full` and `lindy_pilot`

