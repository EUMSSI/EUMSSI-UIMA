EUMSSI UIMA components
======================

This is a meta-repository that contains (links to) the UIMA components used for the EUMSSI.

The actual components are hosted in separate individual repositories and included as submodules (maintained by the EUMSSI project or externally). Additionally a `pom.xml` is provided to compile all needed components with a single command.

## Usage

Check out the repository using `git clone --recursive` to obtain all submodules.

Update repository using `git pull --recurse-submodules`.

Compile and install everything using `mvn clean install` from the repository root.

See https://git-scm.com/book/en/v2/Git-Tools-Submodules for more information on using git submodules.

## Advanced

 `git pull --recurse-submodules` updates everything to the versions marked in the "master" repository. Use `git submodule foreach --recursive git pull --ff-only origin master` to update all submodules to their latest upstream versions. After testing the master repository can then be updated to point to those new versions.
