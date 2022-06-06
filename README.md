# eCSE-archer2-PAS
Contains scripts as they are June 2022, end of eCSE02-06 project.

*The maintained scripts are in https://github.com/knaughten/UaMITgcm/tree/archer2/example/PAS_999/mitgcm_run/scripts/standalone_mit*

These files should be held in the scripts directory for a case, so the subdirectories are:
- run
- build
- scripts
- code

## case_setup
case_setup was introduced to set the environment for the run

It includes the following that should be correctly set:
> export MITGCM_ROOTDIR=/path to installed/MITgcm (in which the tools directory resides)

> account 

> export HECACC=

> here can choose cray or gfortran opt files.

> export MITGCM_OPT=../scripts/dev_linux_amd64_cray_archer2

> export MITGCM_OPT=../scripts/dev_linux_amd64_gfortran_archer2
