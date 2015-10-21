Welcome to .NET Core Documentation
==================================

This is the repository of .NET Core documentation powered by MSDN Open Publishing.

Quick Start
-----------

Start contributing to .NET Core documentation using the following steps:

1. Clone the repo:
   ```
   git clone https://github.com/openpublish/coredocs.git
   ```

2. Edit the Markdown files using your favorite Markdown editor.
3. Commit and push your changes:
   ```
   git add -u
   git commit -m "update doc"
   git push
   ```

4. Wait for a moment and your changes will be automatically published to:
https://msdnnext.redmond.corp.microsoft.com/en-us/openpublishing/corefx/intro-clr

> If you don't have the permission to push to this repo, fork it to your own account and use pull request to submit your changes back.

Validation and Preview
----------------------

Before pushing your changes to remote, you can build and preview your doc in local to discover problems early:

1. To validate your changes, just run `msbuild` under the root of the repo.
2. To preview your changes:
   1. Run `msbuild /t:serve` under the root of the repo.
   2. Open `http://localhost:8000` in your browser.

