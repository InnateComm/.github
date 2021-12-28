<!-- markdownlint-disable -->
<div align="center">
  <img src="https://github.com/github.png" height="100">
  <h1>.github</h1>
  <h2>Community health files for the @CeruleanCodersComm organization</h2>
</div>

<!-- markdownlint-enable -->
<!-- markdownlint-disable first-header-h1 -->
<!-- markdownlint-disable line-length -->
## How does this work?

GitHub will use and display default files for any of our repo that does not have its own file of that type.

Like if a repo in our org, doesn't have a code of conduct, it will inherit from this repo.

You may call this repo as a fallback.

For more information, please see the article on [creating a default community health file for your organization](https://help.github.com/en/articles/creating-a-default-community-health-file-for-your-organization).

## 💣 Reporting Bugs 
<br/>
This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report 📝, reproduce the behavior 💻 💻, and find related reports. 🔎

Since the new GitHub Issue forms we only suggest you to include most information possible. But you can also **Perform a [cursory search](https://github.com/CeruleanCodersComm/.github/issues)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

## 🛠 Reporting good feature requests
<br/>
Bugs are tracked as [GitHub issues](https://github.com/CeruleanCodersComm/.github/issues). After you've determined [which repository](#.github) your bug is related to, create an issue on that repository and provide the following information by filling in [the template](https://github.com/atom/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. 

* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots or animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.

## Cloning the project & creating PR
**1.** Fork [this](https://github.com/CeruleanCodersComm/.github) repository. Click on the <a  href="https://github.com/CeruleanCodersComm/.github"><img  src="https://img.icons8.com/fluency/30/000000/code-fork.png"/></a> symbol at the top right corner.

**2.** Clone the forked repository.

```bash
git clone https://github.com/<your-username>/.github.git
```

**3.** Navigate to the project directory.

```bash
cd .github
```

**4.** Create a new branch (naming convention- type-description-issueNo)

Kindly give your branch a more descriptive name like `docs-contributing-guide-2` instead of `patch-1`.

You could follow this convention. Some ideas to get you started:

*   Feature Updates: `feat-<2-3-Words-Description>-<ISSUE_NO>`
*   Bug Fixes: `fix-<2-3-Words-Description>-<ISSUE_NO>`
*   Documentation: `docs-<2-3-Words-Description>-<ISSUE_NO>`
*   And so on...

```bash
git checkout -b your-branch-name
```

**5.** Make the necessary changes.

**6.** Stage your changes and commit.

```bash
git add . # Stages all the changes
git commit -m "<your_commit_message>"
```


**7.** Push your local commits to the remote repository.

```bash
git push origin your-branch-name
```

**8.** Create a new [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) from `your-branch-name`

🎉 Congratulations! You've made your first pull request! Now, you should just wait until the maintainers review your pull request.



## What is inherited?

- [Code Of Conduct](https://github.com/CeruleanCodersComm/.github/blob/main/CODE_OF_CONDUCT.md) - Contributor Covenant Code of Conduct v2
- [Contributing Guide](https://github.com/CeruleanCodersComm/.github/issues/2) - **Looking for contributors**
- [License](https://github.com/CeruleanCodersComm/.github/blob/main/LICENSE) - MIT License
- [Security Policy](https://github.com/CeruleanCodersComm/.github/blob/main/SECURITY.md) - Informs users on how to report vulnerabilities
- [Issue Templates](https://github.com/CeruleanCodersComm/.github/tree/main/.github/ISSUE_TEMPLATE) - Basic Issue Templates
- [PR Template](https://github.com/CeruleanCodersComm/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md) - Fallback PR Template
