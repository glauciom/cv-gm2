## cv-gm2
LuaLatex of my CV.

Build it using

`./mvnw`

The output will be placed under the folder:

`target/site/resume.pdf`

##Requirements

- Tex Distribution: MacOS Install -> `brew install Caskroom/cask/mactex`)
- Tex Distribution: Instructions for Linux Fedora distro
> yum update && yum install -y texlive fontawesome-fonts texlive-xifthen texlive-fontawesome texlive-datenumber texlive-multirow texlive-tabu
- JRE (in order to run the embedded maven-wrapper latex plugin)
