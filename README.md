# Dashboard

A nightly job checks the status of the GitHub workflow(s) run against
the default branch of each repository listed in ``repositories.json``.

If more than one workflow run against the default branch, it is possible
to check the status of only some workflow(s) by using the ``workflows`` parameter.
Enter the name of the worklow and separate the names using comma.

Each repository should run a daily build so the status can be kept up-to-date.

[Previous runs](./logs/previous.md)

Latest Run


| Owner | Repository | Workflow | Status | Last Run | URL |
| ----- | ---------- | -------- | ------ | -------- | --- |
| ome | [omero-cli-transfer](https://github.com/ome/omero-cli-transfer) | OMERO | ![Success](https://img.shields.io/badge/Success-brightgreen) | 2025-05-04 00:43:11 | [14816070403](https://github.com/ome/omero-cli-transfer/actions/runs/14816070403) |
| German-BioImaging | [omero-tagsearch](https://github.com/German-BioImaging/omero-tagsearch) | PyPI | ![Success](https://img.shields.io/badge/Success-brightgreen) | 2025-04-01 12:41:30 | [14195873142](https://github.com/German-BioImaging/omero-tagsearch/actions/runs/14195873142) |
| TheJacksonLaboratory | [ezomero](https://github.com/TheJacksonLaboratory/ezomero) | Run Tests on push | ![Success](https://img.shields.io/badge/Success-brightgreen) | 2025-04-22 20:18:56 | [14603854938](https://github.com/TheJacksonLaboratory/ezomero/actions/runs/14603854938) |


*Last updated: 2025-05-05 20:39:34*