<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280x640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280x640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
  test
-->

# Deploy to Azure

_Create two deployment workflows using GitHub Actions and Microsoft Azure._

</header>

<!--
  <<< Author notes: Step 6 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 6: Production deployment

_Nice work! :sparkle:_

Great work, you've done it! You should be able to see your container image in the **Packages** section of your account on the main repository page. You can get the deployment URL in the Actions log, just like the staging URL.

### The cloud environment

Throughout the course you've spun up resources that, if left unattended, could incur billing or consume your free minutes from the cloud provider. Once you have verified your application in production, let's tear down those environments so that you can keep your minutes for more learning!

### :keyboard: Activity 1: Destroy any running resources so you don't incur charges

1. Create and apply the `destroy environment` label to your merged `production-deployment-workflow` pull request. If you have already closed the tab with your pull request, you can open it again by clicking **Pull requests** and then clicking the **Closed** filter to view merged pull requests.

Now that you've applied the proper label, let's wait for the GitHub Actions workflow to complete. When it's finished, you can confirm that your environment has been destroyed by visiting your app's URL, or by logging into the Azure portal to see it is not running.

2. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
