---
title: GitKraken Browser Extension
description: Discover how to install and use the GitKraken Browser Extension to streamline pull request workflows in GitHub, GitLab, Bitbucket, and Azure DevOps.
taxonomy:
    category: browser-extension
---

<kbd>Last updated: June 2025</kbd> 

The **GitKraken Browser Extension** connects your Git repositories on GitHub, GitLab, Bitbucket, or Azure DevOps with the GitKraken DevEx platform. It helps you track and manage pull requests with a unified view in Launchpad, simplifying what to work on next.

***

## Requirements

* Google Chrome, Mozilla Firefox, or Microsoft Edge
* [GitKraken Desktop](https://www.gitkraken.com/git-client/try-free) or [GitLens](https://www.gitkraken.com/gitlens/try-free) for Visual Studio Code

***

## How to add the extension

To install the GitKraken Browser Extension:

1. Go to your browser's extension store:
   * <a href="https://chrome.google.com/webstore/detail/gitkraken/egmopflbpgdjmmkeabegohajillnebco">Add GitKraken to Chrome</a>
   * <a href="https://addons.mozilla.org/en-US/firefox/addon/gitkraken-browser-extension/">Add GitKraken to Firefox</a>
   * <a href="https://microsoftedge.microsoft.com/addons/detail/gitkraken/eehliiniplilmbgcnghhaneefihofjnl">Add GitKraken to Edge</a>
2. Select <kbd>Add to [Browser]</kbd> or <kbd>Get</kbd>.

<div class='callout callout--basic'>
    <p>For Firefox, you must manually allow permissions for each Git service. Select the extension icon while on the service’s site, click the gear icon, then choose <kbd>Always Allow on {service}</kbd>.</p>
    <figure>
        <img src='/wp-content/uploads/be-firefox-allow.png' class='img-bordered img-responsive center'>
        <figcaption style="color: #888; text-align: center;">Allowing service permissions in Firefox</figcaption>
    </figure>
</div>

***

## Features

### Code Suggest

Code Suggest allows you to suggest and edit code across the entire project—not just changed lines—when reviewing pull requests in GitLens, GitKraken Desktop, or gitkraken.dev.

You can:
- Suggest code changes in open pull requests.
- Review and accept suggestions in:
  - [GitKraken Desktop](/gitkraken-client/pull-requests/#review-code-and-suggest-changes)
  - [GitLens](gitlens/gitlens-features/#code-suggest-preview)
  - [gitkraken.dev](/gk-dev/gk-dev-home/#code-suggest)

<figure>
    <img src="/wp-content/uploads/gkbe-code-suggest.png" class="img-bordered img-responsive center">
    <figcaption style="color: #888; text-align: center;">Suggest code edits across any part of the PR</figcaption>
</figure>

### Launchpad

The Launchpad dashboard groups pull requests by status: Ready to Merge, Needs My Review, Draft, and more.

You can:
- Open the pull request on the hosting service by selecting the PR number.
- Open the repo in GitKraken Desktop or GitLens by selecting the GitKraken logo.

<figure>
    <img src="/wp-content/uploads/gkbe-launchpad.png" class="img-bordered img-responsive center">
    <figcaption style="color: #888; text-align: center;">See pull requests grouped by workflow status</figcaption>
</figure>

### Open repositories, comparisons, and commits

**Open with GitKraken**: Use GitHub's and GitLab’s Clone dropdowns to open the repository in GitKraken Desktop or GitLens.

<figure>
    <img src="/wp-content/uploads/be-clone.png" class="img-bordered img-responsive center">
    <figcaption style="color: #888; text-align: center;">Open repositories directly in GitKraken or GitLens</figcaption>
</figure>

**Open Comparison in Visual Studio Code**: From a pull request view, select "Open Comparison in VS Code" for a seamless transition into GitLens.

<figure>
    <img src="/wp-content/uploads/be-pull-request.png" class="img-bordered img-responsive center">
    <figcaption style="color: #888; text-align: center;">Open PR comparisons directly in VS Code</figcaption>
</figure>

**Open with GitKraken on commit pages**: Adds a button on commit pages of supported Git services.

<figure>
    <img src="/wp-content/uploads/be-commit.png" class="img-bordered img-responsive center">
    <figcaption style="color: #888; text-align: center;">Quickly access commits using the extension</figcaption>
</figure>

### Opening in GitKraken Desktop

<figure>
    <img src='/wp-content/uploads/gkc-be-open-repo.gif' class='img-bordered img-responsive center'>
    <figcaption style="color: #888; text-align: center;">Open repositories directly in GitKraken Desktop</figcaption>
</figure>

### Opening in GitLens

<figure>
    <img src='/wp-content/uploads/gl-be-open-repo.gif' class='img-bordered img-responsive center'>
    <figcaption style="color: #888; text-align: center;">Open repositories directly in GitLens</figcaption>
</figure>


