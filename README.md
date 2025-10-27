# Dashboard

A nightly job checks the status of the GitHub workflow(s) run against
the default branch of each repository listed in [repositories.json](repositories.json).

If more than one workflow run against the default branch, it is possible
to check the status of only some workflow(s) by using the ``workflows`` parameter.
Enter the name of the worklow and separate the names using comma.

Each repository should run a daily build so the status can be kept up-to-date.

[Previous runs](./logs/previous.md)

[Latest Run](./logs/latest.md)


*Last updated: 2025-10-27 03:22:02*