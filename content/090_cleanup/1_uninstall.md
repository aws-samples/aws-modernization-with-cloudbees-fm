---
title: "Uninstall Apps"
chapter: false
weight: 1
--- 

In this section you will unregister the app that you created in CloudBees Feature Management account and remove the GitHub apps. If required, you can also remove the GitHub Organizations that you created earlier.

### Uninstall app from CloudBees Feature Management Account 

1. Open the CloudBees Feature Management console
2. Select the the blue panel in the top left corner of the screen and select the application that you created earlier.
3. In the application dashboard, click the **App Settings** panel seen on the left hand menu. From the resulting page, select the **Delete App** tab.
4. Click **Delete** to confirm.

### Uninstall CloudBees Feature Management Workshop GitHub App

**CloudBees Feature Management Workshop GitHub App** automatically creates the repositories and webhooks required to complete this lab. By removing the GitHub App, you are confirming that the lab repositories will be removed from your GitHub Organization.

1. Open your browser to the Github Organization you created for the workshop and navigate to the **Settings** tab.
2. Select **Installed GitHub Apps** from the left panel.
3. On **CloudBees Feature Management WS** app, select **Configure**
4. On **Uninstall "CloudBees Feature Management WS"** section, select **Uninstall**


### Optional: Delete GitHub Organizations

If you previously created a new GitHub Organization for this workshop, you can use the following steps to delete the GitHub Organization.

1. Ensure that you are logged into GitHub.com and then navigate to this [link to view your GitHub Organization](https://github.com/account/organizations). 
2. Select the GitHub Organization that you created earlier and click **Settings**
3. On the Organization profile, scroll down to the **Danger zone**
4. Click **Delete this organization**
5. Follow the steps on the screen to confirm deletion of this GitHub Organization.

**Note :** if you wish to keep the GitHub Organization, consider to remove the webhooks created by the GitHub app earlier (see the following section)

### Optional: Remove the webhooks

If you decided to keep the GitHub Organization that you use during the workshop, you can use the following steps to remove the webhooks that was automatically created by the GitHub app.

1. Ensure that you are logged into GitHub.com and then navigate to this [link to view your GitHub Organization](https://github.com/account/organizations). 
2. Select the GitHub Organization that you created earlier and click **Settings**
3. On the left panel, select **Webhooks**
4. Locate two webhooks with name starting `https://cbci.workshop.cb-sa.io/***` 
5. Click **Delete** to remove the webhooks. Repeat the steps to delete both webhooks.

