# Power Apps Canvas Code Library
This repository is a Library of independant Power Apps Canvas code "snippets". [Power Apps Code View](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/code-view) is a feature in **Preview** for now.
This feature allows makers to see a YAML code representation of their Power Apps Canvas, Copy it, and Paste it.

This repository aims to provide a centralized library of interesting snippet of Canvas YAML Code for the community to paste in their own canvas to speed up their Power Apps Canvas and Custom Pages development. 

## Repository Organization
Each code snippet has its own folder in this Repo. Within the folder you can find :
- a **YAML file**, with the same name of the folder, that contains the Canvas YAML Code
- a **README file** with detailed description and usage instructions

## How to use the code
1. Navigate between subfolders inside "/yaml-snippets" folder of this repo to find the code you need.
2. Open the yml file and copy its content
![Copy YAML From GitHub Repo](/.github/assets/copyYmlFromGitHub.png)
3. In Power Apps Canvas Studio, select the location where you want to copy the code (can be at the screen level, or at a container level), Open the menu, Open the Paste submenu, select Paste code :
![Paste YAML in Canvas Studio](/.github/assets/pasteYmlInStudio.png)

## Canvas YAML code organization
The code snippets should be inside Containers to ease the integration in your Canvas. 
Buttons might be outside the Containers, as they would only be Sample buttons, used to simulate behavior properties in your apps and explaining behaviour formulas expected for the code to work.

Comments might be added within the code snippet to help you with the configuration.

## Contribution
Contribution are welcome ! Follow the [Contribution instructions](/CONTRIBUTING.md).