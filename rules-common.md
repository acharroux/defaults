# brief: common rules for all projects

## CLEAN-PROJECT-AI-DEBUG
Put all debug, tests, investigations artifacts you may need for your own purpose into a folder named `debug`: test data, debug/test scripts, tools, ...
Organize it into subfolders with an horodated name like `YYYY-MM-DD-<subject>`
This folder does not have to be clean automatically but consider it as transient: all files inside may disappear between sessions

## KEEP-JOURNAL
Manage a file ` journal.md` at top of project. It will contain a one line abstract of all significative activity grouped by day.
Ex:
2026-04-13
- fix issue about missing dependency
- define a list of unit tests and start to implement it

## CLEAN-INTERNAL-DOCUMENTATION
While planning, implementing, testing, explaining, you typically have to create internal documentation files : architecture,diagrams,readmes,tech notes,benchmarks,reports of any kind, ...
Everything that may be useful to understand internals of this project
Keep these internal documentation files into a folder named `internal-documentation`. Organize it into subfolders for each important topic

## CLEAN-SCRIPTS-TOOLS
keep all permanent tools and scripts associated to this project for build, test, debug,setup,.. into a folder named `scripts-tools`
each tool/script must be kept into a dedicated sub-folder containing the script and associated files (readme.md, config files,...)

## CLEAN-EXPERIMENTS
Experiments are subsets, variants, experimental implementations, debug/verbose builds, connex ideas,... of this project. They are not part of the main project but
are still directly related to it and are not considered as temporary as the ones in `debug`. All files related to an experiment must be kept under a subfolder of folder `experiments`

## CLEAN-RELEASE
when asked to make a release, all final artefacts (executables,installers,pcakages,...) must be copied into a folder named `deploy/<platform>/<build kind>/<version>` as well as a minimum of 2 documents
- `readme.md`: basic usage
- `deploy.md`: minimal instructions for deploy
- `release-notes.md`: abstract of the new features compiled from journal.md and other non interna documents

## CLEAN-VERSION
a file named `version.md` keep track of the current semantic version


