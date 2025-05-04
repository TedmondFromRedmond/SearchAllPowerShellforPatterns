# SearchAllPowerShellforPatterns
Used for Azure deprecated cmdlet deprecation. Microsoft has deprecated Azure AD cmdlets. use this to discover scripts with deprecated cmdlets.

This is a version of the SearchAllFilesforPatterns modified for PowerShell files only.

**To Use:**
1. Download the source SearchAllPowerShellforPatterns.ps1
2. Download the cmdletMaps.txt file for input
3. One can either modify the Overrides section or use parameters

**Script is self documented and one can use get-help to discover usage statements and other details.**
e.g. get-help .\SearchAllPowerShellforPatterns.ps1

**Microsoft References for deprecated commandlets:**
 https://techcommunity.microsoft.com/t5/microsoft-entra-blog/important-update-deprecation-of-azure-ad-powershell-and-msonline/ba-p/4094536
* April 1st, 2024 - more AD literature on deprecation of cmdlets
  https://learn.microsoft.com/en-us/powershell/module/azuread/?view=azureadps-2.0
 * Deprecated Azure cmdlet listings
        https://learn.microsoft.com/en-us/powershell/microsoftgraph/azuread-msoline-cmdlet-map?view=graph-powershell-1.0

**Sample output in CSV format is:**
FolderandFileName	Pattern	LastWriteTime	FileSize	OccurenceLocations
D:\Backups\20201019-Backups-Documents\PowerShell\Scripts\mytest.ps1


Future versions could include:
------------------------------
- GUI on top of script to review and replace,mark findings
- AI replacement suggestions for findings

The paid for service by CIO Services includes a Complexity rating for each script based upon a well known NIST code.
For more information regarding paid for services, contact Paul_Harker@CIONational.com


