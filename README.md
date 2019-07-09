# GitVersion View README

![alt text](https://raw.githubusercontent.com/HSSE-Dev/GitVersionView/master/images/presentation.gif)

GitVersion View displays the current version of the checked out branch in the status bar. The display format can be customized to your needs.</br>
Unfortunately it is still necessary that GitVersion is installed locally, because the extension accesses it, see [here](#Requirements). </br>
With the recently released VSCode 1.36 you can show and hide status bar items as you like, see [here](https://code.visualstudio.com/updates/v1_36).</br>
__Enjoy!__

## Requirements

Install GitVersion on your system - see here
[Install GitVersion CMD Tool](https://gitversion.readthedocs.io/en/latest/usage/command-line/)

## Extension Settings

This extension contributes the following settings:

* `gitVersionView.versionFormat`: specify the output format [GitVersion Variables](https://gitversion.readthedocs.io/en/latest/more-info/variables/)<br/> 
Supported: "SemVer", "MajorMinorPatch", "InformationalVersion"

## For more information
* [GitHub Issues](https://github.com/HSSE-Dev/GitVersionView/issues)
* [Email](HSSE-Development@outlook.com)
* [Link to Microsoft Marketplace](https://marketplace.visualstudio.com/items?itemName=HSSE-Development.gitversionview)

-----------------------------------------------------------------------------------------------------------

## Release Notes

## 0.1.4
- Update NPM Dependencies to prevent vulnerabilities
- Update README text
- add GIF to README
  
## 0.1.3
- added Keywords/Tag for marketplace

### 0.1.2
- fix marketplace banner

### 0.1.1
- disable popup message on start and repo change

### 0.1.0
- Initial release of GitVersion View