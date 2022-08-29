# How To Install and Use Fragment
Thank you for installing Fragment and joining the alpha program! This guide will help you through the installation and initial usage of the Fragment technical preview.

## GitHub Setup
In order to store your files, Fragment utilizes GitHub as a backend. This ensures that your data is never stored on Fragment servers or anywhere on our systems. First, create a GitHub account at [https://github.com/signup](). 

Once you have your account set up, you need to generate a `Personal Access Token`. Fragment uses this token to upload and download files and interact with Git in general. 

First, navigate to your account settings. Click on your profile icon in the upper right corner and select `Settings` near the bottom of the dropdown. Next, choose the last option called `Developer Settings` on the left side menu of the settings page:

| Github Settings           | Developer Settings        |
|---------------------------|---------------------------|
| ![](/doc/gitsettings.png) | ![](/doc/devSettings.png) |

Next, choose the menu option titled  `Personal Access Token` and then click on `Generate Token`:

| PAT               | Generate Token      |
|-------------------|---------------------|
| ![](/doc/PAT.png) | ![](/doc/token.png) |

On the next page, you must set token permissions. This tells Fragment what Git functionality it is allowed to access. Give your token any name you want. Also set the token expiration date to anything you want. When this expires, you will need to generate a new token in order to use Fragment. The only permissions required to run Fragment in a full configuration are as follows:

| Repo Settings      | User Settings      |
|--------------------|--------------------|
| ![](/doc/repo.png) | ![](/doc/read.png) |

Next, generate your token and copy it to the clipboard. Make sure to save this token somewhere you won't forget it. You may now use this token to log into Fragment using your GitHub account.

| Token                 |
|-----------------------|
| ![](/doc/dontcopy.png)_ |

