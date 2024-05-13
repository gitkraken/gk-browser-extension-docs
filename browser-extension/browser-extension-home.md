---

title: GitKraken Browser Extension
description: Learn all about the GitKraken Browser Extension.
taxonomy:
    category: browser-extension

---

The GitKraken Browser Extension bridges the gap between your repositories on GitHub, GitLab, Bitbucket, or Azure DevOps, and the GitKraken DevEx platform. It allows you to easily access pull requests in an organized view via the launchpad to know what needs to be worked on next and begin working with GitKraken. 

***

## Requirements

* Google Chrome, Mozilla Firefox or Microsoft Edge
* [GitKraken Desktop](https://www.gitkraken.com/git-client/try-free) or [GitLens](https://www.gitkraken.com/gitlens/try-free) for Visual Studio Code

***

## How to add the extension

To add the browser extension, navigate to the following link for your respective browser and select `Add to [Browser]` or `Get`:
* [Google Chrome](https://chrome.google.com/webstore/detail/gitkraken/egmopflbpgdjmmkeabegohajillnebco)
* [Mozilla Firefox](https://addons.mozilla.org/en-US/firefox/addon/gitkraken-browser-extension/)
* [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/gitkraken/eehliiniplilmbgcnghhaneefihofjnl)

<div class='callout callout--basic'>
    <p>For Firefox, you will need to manually allow permissions for the respective service in order to see these features. This can be done by selecting the extension icon when on the site for the service, then selecting the gear icon, and then selecting <kbd>Always Allow on {service}</kbd>.</p>

    <p><img src='/wp-content/uploads/be-firefox-allow.png' class='img-bordered img-responsive center'></p>
</div>


***

## Features

### Code Suggest

GitKraken Code Suggest simplifies code review by allowing you to make suggestions and edits across the entire project, not just on the lines that were changed, within GitLens, GitKraken Desktop, and gitkraken.dev. When a Pull Request is open, you can make suggestions to the pull request that others can then review and accept to include in the pull request. When there are code suggestions on a pull request, you can select `Code Suggestions` to open and review it on [GitKraken Desktop](), [GitLens](gitlens/gitlens-features/#code-suggest-preview), or [gitkraken.dev](/gk-dev-home/#code-suggest). 

<img src="/wp-content/uploads/gkbe-code-suggest.png" class="img-bordered img-responsive center">

### Launchpad

The Launchpad is a unified dashboard that consolidates pull requests across all of the repositories and groups them based on the state of the pull request - Ready to Merge, Unassigned Reviewers, Resolve Conflicts, Needs My Review, Suggested Changes, Reviewer Commented, Waiting for Review, Draft, and Other. 

Select the pull request #number to open the pull request on your hosting service or select the GitKraken logo to open the repository in GitKraken Desktop or GitLens.

<img src="/wp-content/uploads/gkbe-launchpad.png" class="img-bordered img-responsive center">

### Opening repositories, comparisons, and commits

Open with GitKraken: From GitHub's Code and GitLab’s Clone dropdowns, you can open a repository directly in GitKraken Desktop or with GitLens in Visual Studio Code.

<img src="/wp-content/uploads/be-clone.png" class="img-bordered img-responsive center">

Open Comparison in Visual Studio Code: From the pull request view on GitHub, GitLab, Bitbucket, or Azure DevOps, you can select "Open Comparison in VS Code" from the Code dropdowns for an easy transition into GitLens in Visual Studio Code.

<img src="/wp-content/uploads/be-pull-request.png" class="img-bordered img-responsive center">

Open with GitKraken button on commit pages: The GitKraken Browser extension adds a dedicated "Open with GitKraken" button to GitHub's, GitLab’s, Bitbucket's, or Azure DevOp's commit pages.

<img src="/wp-content/uploads/be-commit.png" class="img-bordered img-responsive center">

### Opening in GitKraken Desktop

<img src='/wp-content/uploads/gkc-be-open-repo.gif' class='img-bordered img-responsive center'>

### Opening in GitLens

<img src='/wp-content/uploads/gl-be-open-repo.gif' class='img-bordered img-responsive center'>