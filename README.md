EUMSSI UIMA components
======================

This is a meta-repository that contains (links to) the UIMA components used for the EUMSSI.

The actual components are hosted in separate individual repositories and included as submodules (maintained by the EUMSSI project or externally). Additionally a `pom.xml` is provided to compile all needed components with a single command.

## Usage

Check out the repository using `git clone --recursive` to obtain all submodules.

Compile and install everything using `mvn clean install` from the repository root.
