# HOW TO CONTRIBUTE
Thank you for your interest in contributing in this repo for the Power Apps Community !

This repo is still a Work In Progress, enhancement will be made to the contribution process over time.

## Repo organization
This repository is a Library of independant Power Apps Canvas code snippets.
Each code snippet is identified by a "code snippet code" that is a short descriptive string describing the code snippet. This Code is in "kebab-case" (example: "gallery-table"). Each code snippet has it's own folder named with the code snippet code inside the "/yaml-snippets" folder.
Inside each code snippet folder, is structured the same way :
- `assets` folder to store assets such as Images or Documents. As a global image is expected, it should be stored in this folder using the code snippet code as name (gif authorized).
- `sample-code-snippet.yml` YAML file with the Power Apps Canvas YAML Code, named with the code snippet code.
- `README.md` a descriptive Markdown file of the code snippet with predefined content organization. An Image of the Canvas result is expected on the top of this MD File.

## Contribution Process
1. Get your own copy of the code using using a Fork
2. You should always ensure that your fork is up-to-date with the upstream repository by regularly synchronizing your fork.
The simplest way to synchronize your fork with the upstream repository is via the Fetch upstream feature on your fork github page
3. Create your own branch. Your branch should be name as "{CodeSnippetCode}/{ShortUpdateDescription}" (example: `gallery-table/ColumnVisibility`)
4. If you are submitting a new code snippet, you can copy the ["zz-sample-code-snippet" ](/yaml-snippets/zz-sample-code-snippet/) folder to ensure you are following the expected folder organization. This Sample folder includes 
   1. `assets` folder with the properly name global image inside.
   2. The properly named YAML file with Canvas Code. 
   YAML is generated from Canvas Studio this way :
   ![Copy YAML From Power Apps Canvas Studio](/.github/assets/copyYmlFromStudio.png)
   3. `README` file with all required sections inside.
5. When your work is ready for submission, create a Pull Request from your branch in your own fork into the main branch in this repository. Each PR should include only updates for a single code snippet.

## Code quality
The provided YAML should always be :
- Inside a layout container, to ease pasting and insertion experience inside an existing canvas **OR** an entire screen.
- Independant : 
  - Not using any custom datasource
  - Not using any canvas or code component
  - Using sample data. Buttons could be added to run `Set()`, `ClearCollect()` or `UpdateContext()` functions, creating Sample Data and/or trigger behaviors for Code snippet demonstration.
- Respecting canvas [Naming convention](https://www.microsoft.com/en-us/power-platform/blog/power-apps/powerapps-canvas-app-coding-standards-and-guidelines/) (Latest PDF version available at the end of the blog post)
- Commented as much as possible to help makers to understand the logic and how/where to add their custom PowerFx formulas.
  
**These rules will be verified when validating your Pull Request.**