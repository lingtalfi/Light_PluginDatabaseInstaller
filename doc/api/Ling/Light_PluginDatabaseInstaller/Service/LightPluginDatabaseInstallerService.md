[Back to the Ling/Light_PluginDatabaseInstaller api](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller.md)



The LightPluginDatabaseInstallerService class
================
2019-09-11 --> 2019-09-11






Introduction
============

The LightPluginDatabaseInstallerService class.



Class synopsis
==============


class <span class="pl-k">LightPluginDatabaseInstallerService</span>  {

- Properties
    - protected string [$appDir](#property-appDir) ;
    - protected array [$installers](#property-installers) ;

- Methods
    - public [__construct](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/__construct.md)() : void
    - public [registerInstaller](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/registerInstaller.md)(string $pluginName, [Ling\Light_PluginDatabaseInstaller\LightPluginDatabaseInstallerInterface](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/LightPluginDatabaseInstallerInterface.md) $installer) : void
    - public [install](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/install.md)(string $pluginName) : void
    - public [isInstalled](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/isInstalled.md)(string $pluginName) : bool
    - public [uninstall](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/uninstall.md)(string $pluginName) : void
    - public [uninstallAll](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/uninstallAll.md)() : void
    - public [setAppDir](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/setAppDir.md)(string $appDir) : void
    - protected [getFilePath](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/getFilePath.md)(string $pluginName) : string

}




Properties
=============

- <span id="property-appDir"><b>appDir</b></span>

    This property holds the appDir for this instance.
    
    

- <span id="property-installers"><b>installers</b></span>

    This property holds the installers for this instance.
    
    It's an array of pluginName => LightPluginDatabaseInstallerInterface
    
    



Methods
==============

- [LightPluginDatabaseInstallerService::__construct](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/__construct.md) &ndash; Builds the LightPluginDatabaseInstallerService instance.
- [LightPluginDatabaseInstallerService::registerInstaller](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/registerInstaller.md) &ndash; Registers the given installer for the given plugin.
- [LightPluginDatabaseInstallerService::install](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/install.md) &ndash; Installs the database part of the given plugin.
- [LightPluginDatabaseInstallerService::isInstalled](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/isInstalled.md) &ndash; Returns whether the given plugin's database part is installed.
- [LightPluginDatabaseInstallerService::uninstall](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/uninstall.md) &ndash; Uninstalls the database part of the given plugin.
- [LightPluginDatabaseInstallerService::uninstallAll](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/uninstallAll.md) &ndash; Uninstalls the database parts for all plugins (which database part was previously installed).
- [LightPluginDatabaseInstallerService::setAppDir](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/setAppDir.md) &ndash; Sets the appDir.
- [LightPluginDatabaseInstallerService::getFilePath](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/Service/LightPluginDatabaseInstallerService/getFilePath.md) &ndash; Returns the path to the **pluginA.installed** file for the given plugin.





Location
=============
Ling\Light_PluginDatabaseInstaller\Service\LightPluginDatabaseInstallerService<br>
See the source code of [Ling\Light_PluginDatabaseInstaller\Service\LightPluginDatabaseInstallerService](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/Service/LightPluginDatabaseInstallerService.php)



SeeAlso
==============
Previous class: [LightPluginDatabaseInstallerInterface](https://github.com/lingtalfi/Light_PluginDatabaseInstaller/blob/master/doc/api/Ling/Light_PluginDatabaseInstaller/LightPluginDatabaseInstallerInterface.md)<br>
