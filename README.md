# Timeline Sample from SharePoint List (Dynamic Values)

## Summary

This web part is a sample in how you can create a Beautiful TIMELINE with dynamic values from a SharePoint List 

- [Here]()

![SAMPLE](./assets/timeline.gif)

## Compatibility

| :warning: Important          |
|:---------------------------|
| Every SPFx version is only compatible with specific version(s) of Node.js. In order to be able to build this sample, please ensure that the version of Node on your workstation matches one of the versions listed in this section. This sample will not work on a different version of Node.|
|Refer to <https://aka.ms/spfx-matrix> for more information on SPFx compatibility.   |

This sample is optimally compatible with the following environment configuration:

![SPFx 1.17.0](https://img.shields.io/badge/SPFx-1.17.0-green.svg)
![Node.js v16 | v17 | v12](https://img.shields.io/badge/Node.js-v16%20%7C%20v17-green.svg)
![Compatible with SharePoint Online](https://img.shields.io/badge/SharePoint%20Online-Compatible-green.svg)
![Does not work with SharePoint 2019](https://img.shields.io/badge/SharePoint%20Server%202019-Incompatible-red.svg "SharePoint Server 2019 requires SPFx 1.4.1 or lower")
![Does not work with SharePoint 2016 (Feature Pack 2)](https://img.shields.io/badge/SharePoint%20Server%202016%20(Feature%20Pack%202)-Incompatible-red.svg "SharePoint Server 2016 Feature Pack 2 requires SPFx 1.1")
![Local Workbench Unsupported](https://img.shields.io/badge/Local%20Workbench-Unsupported-red.svg "Local workbench is no longer available as of SPFx 1.13 and above")
![Hosted Workbench Compatible](https://img.shields.io/badge/Hosted%20Workbench-Compatible-green.svg)
![Compatible with Remote Containers](https://img.shields.io/badge/Remote%20Containers-Compatible-green.svg)

For more information about SPFx compatibility, please refer to <https://aka.ms/spfx-matrix>

## Applies to

- [SharePoint Framework](https://learn.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
- [Microsoft 365 tenant](https://learn.microsoft.com/sharepoint/dev/spfx/set-up-your-development-environment)

> Get your own free development tenant by subscribing to [Microsoft 365 developer program](http://aka.ms/m365devprogram)

## Contributors

* [Joao Livio](https://github.com/jtlivio)

## Version history

| Version | Date             | Comments        |
| ------- | ---------------- | --------------- |
| 1.0     | April 08, 2023 | Initial release |


## Minimal Path to Awesome

Create a Custom List

| Name             | Type        |
| ---------------- | --------------- |
| MyAreas | Choice |
| MyShortText | Single line of text |
| MyHyperlink | Hyperlink or Picture |
| MyIconRgb | Single line of text	|
| MyIcon | Choice |
| MyCardTitle | Single line of text |


- Clone this repository (or [download this solution as a .ZIP file]() then unzip it)
- From your command line, change your current directory to the directory containing this sample (`react-timeline-3rdparty`, located under `samples`)
- in the command line run:
  - `npm install`
  - `gulp serve`


## Features

- Create Timeline from SharePoint List (Dynamic Values)e Function, must change
- [Uses react-vertical-timeline-component](https://github.com/stephane-monnot/react-vertical-timeline)
- [Uses pnpJs V3](https://pnp.github.io/pnpjs/getting-started/)
