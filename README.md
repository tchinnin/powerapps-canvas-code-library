# Power Apps Canvas Code Library
This repository is a Library of independant Power Apps Canvas code "blocks". [Power Apps Code View]([https://](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/code-view)) is a feature in **Preview** for now.
This feature allows makers to see a YAML code representation of their Power Apps Canvas, Copy it, and Paste it.

This repository aims to provide a centralized library of interesting block of Canvas YAML Code for the community to paste in their own canvas to speed up their Power Apps Canvas and Custom Pages development. 

## Repository Organization
Each code block has its own folder in this Repo. Within the folder you can find :
- a **YAML file**, with the same name of the folder, that contains the Canvas YAML Code
- a **README file** with detailed description and usage instructions

## Canvas YAML code organization
The provided YAML should always be :
- Inside a layout container, to ease pasting and insertion experience inside an existing canvas.
- Independant : 
  - Not using any custom datasource
  - Not using any canvas or code component
  - Using sample data. Buttons could be added to run `Set()` or `ClearCollect()` function, creating Sample Data for Code block demonstration.
- Respecting canvas [Naming convention]([https://](https://www.microsoft.com/en-us/power-platform/blog/power-apps/powerapps-canvas-app-coding-standards-and-guidelines/)) (Latest PDF version available at the end of the blog post)