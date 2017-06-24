# Change Log

## 1.8.0.6

- Moved to a new repository.
- Added an AppVeyor CI/CD release pipeline.
- Added code coverage support (no tests yet).

## 1.7.0.0

- Added SkipConnectionCheck parameter to some cmdlets to prevent checking of connection
  prior to performing required function.
- Added Update-DSCTools function.

## 1.6.0.0

- Added function Update-DSCNodeConfiguration.
- Improved Handling of calling functions with Localhost.
- Checks to see if remote computers accessible before calling functions.

## 1.4.0.0

- Misc fixes to DSCTools.psm1
- Renamed DSCTools.selftest.* files to DSCTools.Example files and moved to Examples folder

## 1.3.0.0

- Added DSCTools.Package.ps1 Script
- Added Get-xDSCLocalConfigurationManager CmdLet
- Added Set-DSCPullServerLogging Cmdlet

## 1.2.0.0

- Added Install-DSCResourceKit CmdLet
- Added Enable-DSCPullServer CmdLet

## 1.1.0.0

- Allowed Invoke-DSCPull to use a Nodes param
- Added test functions
- Added Configuration ConfigureLCMPushMode
- Added Function Start-DSCPushMode

## 1.0.0.0

- Initial Version
