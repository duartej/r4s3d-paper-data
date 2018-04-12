# r4s3d-paper-data
Data files for R4S 3d paper (provisional directory )

This repository provides some data files needed for the re-creation of the 
plots at: https://gitlab.cern.ch/duarte/r4s3d-paper

The git large file storage feature is used (git-lfs), to be able to store and track
larger data files. They are not part of the std. repository at cern.ch to avoid
blowing up the repository leading to slow I/O for push and pulls.

To use this repository the large file storage extension of git has to be installed.

Installation of git-lfs includes the git-lfs software package and the installation
of the extension to git. Git-lfs is a rather new feature and installation requires
a git version >= 1.8.2. New git version are usually not yet shipped within the
std. repositories thus git usually has to be upgraded first.

A usefull guide for all operating systems can be found here:
https://github.com/git-lfs/git-lfs/wiki/Installation

In summary:
```bash
# Install git-lfs, requires git --version > 1.8.2
# and configure it in your repo. 
$ git clone https://github.com/duartej/r4s3d-paper-data.git
$ cd data
$ git lfs install --local
