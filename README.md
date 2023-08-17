<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280x640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280x640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Deploy to Azure

_Create two deployment workflows using GitHub Actions and Microsoft Azure._

</header>

<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 4: Deploy to a staging environment based on labels

_Nicely done, you used a workflow to spin up your Azure environment :dancer:_

Now that the proper configuration and workflow files are present, let's test our actions! In this step, there's a small change to the game. Once you add the appropriate label to your pull request, you should be able to see the deployment!

1. Create a new branch named `staging-test` from `main` using the same steps as you did for the previous `azure-configuration` branch.
1. Edit the `.github/workflows/deploy-staging.yml` file, and replace every `<username>` with your GitHub username.
1. Commit that change to the new `staging-test` branch.
1. Go to the Pull requests tab and there should be a yellow banner with the `staging-test` branch to `Compare & pull request`. Once the pull request is opened up, click `Create pull request`.

### :keyboard: Activity 1: Add the proper label to your pull request

1. Ensure that the `GITHUB_TOKEN` for this repository has read and write permissions under **Workflow permissions**. [Learn more](https://docs.github.com/en/actions/security-guides/automatic-token-authentication#modifying-the-permissions-for-the-github_token). This is required for your workflow to be able to upload your image to the container registry.
1. Create and apply the `stage` label to your open pull request
1. Wait for the GitHub Actions workflow to run and deploy the application to your Azure environment. You can follow along in the Actions tab or in the pull request merge box. The deployment may take a few moments but you've done the right thing. Once the deployment is successful, you'll see green check marks for each run, and you'll see a URL for your deployment. Play the game!
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
