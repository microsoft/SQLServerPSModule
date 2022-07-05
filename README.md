# ![logo][] SqlServer PowerShell Module

[logo]: https://raw.githubusercontent.com/microsoft/SqlServerPSModule/main/assets/ps_black_64.svg?sanitize=true

This module allows SQL Server developers, administrators and business intelligence professionals to automate database development and server administration, as well as both multidimensional and tabular cube processing.

🚛 Get it via the PowerShell gallery: https://www.powershellgallery.com/packages/SqlServer

🔎 Cmdlet Reference: https://docs.microsoft.com/powershell/module/sqlserver/


## Feedback Repository

This repository is available for triaging and addressing feedback on the SqlServer PowerShell module. We welcome community interaction and suggestions!


## New to PowerShell?

If you are new to PowerShell and would like to learn more, we recommend reviewing the [getting started][] documentation.

[getting started]: https://github.com/PowerShell/PowerShell/tree/master/docs/learning-powershell

## Installing or updating the SqlServer module

To install the **SqlServer** module from the PowerShell Gallery, start a [PowerShell](/powershell/scripting/overview) session as an administrator. You can also start Azure Data Studio as an administrator and run these commands in a PowerShell session in the integrated terminal.

You can also use *Install-Module SQLServer -Scope CurrentUser* to run elevated permissions. This cmdlet is useful for users who aren't administrators in their environment. However, since the scope is limited to the current user, other users on the same machine can't use the module.

### Install the SqlServer module

Run the following command in your PowerShell session to install the SqlServer module for all users:

```powershell
Install-Module -Name SqlServer
```

### To view the versions of the SqlServer module installed

Execute the following command to see the versions of the SqlServer module that have been installed

```powershell
Get-Module SqlServer -ListAvailable
```

### Install for the current user rather than as an administrator

If you aren't able to run the PowerShell session as an administrator, install for the current user using the following command:

```powershell
Install-Module -Name SqlServer -Scope CurrentUser
```

### To overwrite a previous version of the SqlServer module

You can also use the `Install-Module` command to overwrite a previous version.

```powershell
Install-Module -Name SqlServer -AllowClobber
```

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
