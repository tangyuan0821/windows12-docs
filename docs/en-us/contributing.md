---
title: Contributing Guide
layout: default
parent: English
nav_order: 3
permalink: /en-us/contributing
---

<details close markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---
# Contributing Guide

Thank you to all developers who have contributed to this project and everyone's support!

If you like this project, welcome to give this project a Star, sponsor us or make some important contributions qwq~

Please don't submit meaningless PRs~ Here we specifically criticize:
<img width="673" alt="image" src="https://github.com/tjy-gitnub/win12/assets/121747915/2da6f2d8-369a-4ef7-a87e-7ac4ecacd78b">

## Bug Reporting

1. Please use the latest version to confirm whether the bug has been fixed.

2. Please confirm whether the bug or error belongs to the issues you are using. For example, using older browsers (such as IE, etc.), turning off some browser features (such as prohibiting data storage, etc.)

3. Please clearly describe the bug so that we can better fix it.

4. You can use the "Bug Report" Issue template for feedback, but please fill in the content correctly.

5. It is prohibited to add any content that violates laws or is politically sensitive, otherwise it will be locked + banned depending on the situation.

## Making Suggestions

1. Please use the latest version to confirm whether the suggestion has been implemented/resolved.

2. Please clearly describe the suggestion so that we can better implement/resolve it.

3. You can use the "Make Suggestion" Issue template for feedback, but please fill in the content correctly.

4. It is prohibited to add any content that violates laws or is politically sensitive, otherwise it will be locked + banned depending on the situation.

## Code Submission

Note: Please strictly follow the development specifications below and at the beginning of desktop.html to edit the code, otherwise it will not be merged

1. Please try to commit all content in one Commit. You can add Commits, but try not to exceed 5 Commits.

2. Please try to use Git command line, Github Desktop, [https://github.dev](https://github.dev/tjy-gitnub/win12) and other methods for submission. Please do not upload files directly in the browser for submission.

3. It is prohibited to upload any content that violates laws or is politically sensitive, otherwise it will be locked + banned depending on the situation (Tip: current news is also not allowed).

4. Please do not randomly choose submission titles and content when submitting, for example:

   - Good examples: Fix the problem that xx cannot be used normally, add xx application
  
   - Bad examples: Ababa, forgot to do this thing, too many bugs...qwq

5. Formatting requirements:

   - Please do not use formatting tools to format HTML files

   - For JavaScript and CSS files, you can use the formatting tool that comes with Visual Studio Code

### Commit Message Requirements

   1. If the update has a certain importance or magnitude, please follow the following format:

      ```
      v11.4.5 - Updated xxx

      (Update from @Somebody)
      - Updated...
      - Optimized...
      - Fixed...
      ...
      ```

      - Requirements for using this format:

         1. This update must be notified to us before submission.

      - Description:

         1. The title should include version number and main update content.

         2. The first line of content should indicate the update source.

         3. The content should use a list format to describe the update content.

      - Note:

         1. Please do not arbitrarily select version numbers. If you are not sure, you can contact us through our communication group (<https://teams.live.com/l/invite/FEA0yrNkE_bAn-ddwI>) and get assigned a version number.

         2. When updating, remember to add relevant content about the update in the update log of the "About Windows 12 Web Version" application.

   2. If the following conditions are met, the submission content is not subject to overly standard regulations:

      - Less update content.

      - Update content has no important changes.

      Although there are no standard regulations, it is still necessary:

         1. The submission title should be clear and concise, and can briefly summarize the main content of the update.

         2. The submission content should indicate the submitter and describe the content of this update in a list or other way.

### Development Specifications

1. Regulations for HTML files

   See the code specifications at the beginning of `desktop.html`, be sure to read carefully.

2. Regulations for JS files

   1. Please develop according to the following code style:

   ```js
      var sum = 0;
      for (var i = 0; i < 10; i++) {
         sum += i;
      }
      console.log(sum);
   ```

   2. For function names and variable naming, please use camelCase naming, such as:

      - isLoaded

      - storagedItems

   3. For class names, please use PascalCase (UpperCamelCase), such as:

      - WindowManager

      - Widgets

   4. Regulations for code specifications:

      1. For those codes that do not need to be expanded, try to compress them into one line
