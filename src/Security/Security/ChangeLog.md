<!--
    Please leave this section at the top of the change log.

    Changes for the upcoming release should go under the section titled "Upcoming Release", and should adhere to the following format:

    ## Upcoming Release
    * Overview of change #1
        - Additional information about change #1
    * Overview of change #2
        - Additional information about change #2
        - Additional information about change #2
    * Overview of change #3
    * Overview of change #4
        - Additional information about change #4

    ## YYYY.MM.DD - Version X.Y.Z (Previous Release)
    * Overview of change #1
        - Additional information about change #1
-->
## Upcoming Release
* Fixed miscellaneous typos across module
* Add CosmosDB ATP to md files

## Version 0.7.5
* Use NextLink for return maximum of 1500 security alerts in command Get-AzSecurityAlert

## Version 0.7.4
* Deprecate ResourceGroupName parameter in commands: Get-AzSecurityPricing and Set-AzSecurityPricing

## Version 0.7.3
* Split `Set-AzSecurityThreatProtection` into two new cmdlets:
    - `Disable-AzSecurityAdvancedThreatProtection`
    - `Enable-AzSecurityAdvancedThreatProtection`
* Rename `Get-AzSecurityThreatProtection` to `Get-AzSecurityAdvancedThreatProtection`

## Version 0.7.2
* Add new cmdlets: Get-AzSecurityThreatProtection and Set-AzSecurityThreatProtection

## Version 0.7.0
* Update Set-AzSecurityContact. Phone, AlertAdmin, NotifyOnAlert parameters are no longer mandatory
