# README

* The application `diag_run` is used to run NorESM diagnostics packages from the command line.

* All future modifications to `diag_run` and the associated diagnostics packages are documented by Github (https://github.com/NordicESMhub/NoresmDiagnostics).

* `diag_run` is an executable bash application, wrapping around the different bash/csh shell scripts, used to run the diagnostics of each of the NorESM components.
Hence, instead of modifying each bash/csh script manually for each component, `diag_run` enables the user to run and configure each package from the command line.

* At the moment, the atmospheric (CAM), land (CLM) and sea-ice (CICE), ocean (MICOM) and carbon-cycle (HAMOCC) diagnostics packages have been implemented to `diag_run`.

* The code to those packages are located in ./CAM_DIAG, ./CLM_DIAG, ./CICE_DIAG, ./BLOM_DIAG, and HAMOCC_DIAG, respectively.