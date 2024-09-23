# HOW TO CONTRIBUTE
Thank you for your interest in contributing in this repo for the Power Apps Community !

This repo is still a Work In Progress, enhancement will be made to the contribution process over time.

## Repo organization
This repository is a Library of independant Power Apps Canvas code "blocks".
Each code block is identified by a "Code Block Code" that is a short descriptive string describing the code block. This Code is in "CamelCase" (example: "GalleryTable"). Each code block has it's own folder named with the code block code.
Inside each code block folder, is structured the same way :
- `Assets` folder to store assets such as Images or Documents. As a global image is expected, it hsould be stored in this folder using the code block code as name.
- `SampleCodeBlock.yml` YAML file with the Power Apps Canvas Code, named with the code block code.
- `README.md` a descriptive MD file of the code block with predefined content organization. An Image of the Canvas result is expected on the top of this MD File.

## Contribution Process
1. Get your own copy of the code using using a Fork
2. You should always ensure that your fork is up-to-date with the upstream repository by regularly synchronizing your fork.
The simplest way to synchronize your fork with the upstream repository is via the Fetch upstream feature on your fork github page
3. Create your own branch. Your branch should be name as "{CodeBlockCode}/{ShortUpdateDescription}" (example: `GalleryTable/ColumnVisibility`)
4. If you are submitting a new code block, you can copy the "SampleCodeBlock" folder to ensure you are following the expected folder organization. This Sample folder includes 
   1. `Assets` folder with the properly name global image inside.
   2. The properly named YAML file with Canvas Code. 
   3. `README` file with all required sections inside.
5. When your work is ready for submission, create a Pull Request from your branch in your own fork into the main branch in this repository. Each PR should include only updates for a single code block.

## Code quality
The provided YAML should always be :
- Inside a layout container, to ease pasting and insertion experience inside an existing canvas.
- Independant : 
  - Not using any custom datasource
  - Not using any canvas or code component
  - Using sample data. Buttons could be added to run `Set()` or `ClearCollect()` function, creating Sample Data for Code block demonstration.
- Respecting canvas [Naming convention]([https://](https://www.microsoft.com/en-us/power-platform/blog/power-apps/powerapps-canvas-app-coding-standards-and-guidelines/)) (Latest PDF version available at the end of the blog post)

**These rules will be verified when validating your Pull Request.**