<img width="334" alt="image" src="https://github.com/user-attachments/assets/eda108bc-99aa-4b92-8a01-7db999c364e3">

![image](https://github.com/user-attachments/assets/164816f0-31b4-4376-b26c-0f59339828d4)



# My Computer Chocolatey Installation Script

## Introduction
Hello! I’m Aada MacGregor. I have the following programs installed on my computer:
- Google Chrome
- Visual Studio Code
- Git
- Zoom

## Chocolatey Installation Script
```powershell

**Run the following command in Powershell to install CHOCOLATEY**


Set-ExecutionPolicy Bypass -Scope Process -Force; iwr https://community.chocolatey.org/install.ps1 -UseBasicParsing | iex

```


## Step 2: Programs/Apps Installation

 

***The list of apps that you are going to install is as below:*** <br>

***> powershell-core, git, vscode, putty,firefox, greenshot,google-drive-file-stream, googlechrome notepadplusplus, winscp, 7zip,  paint.net, windirstat, zoom, sudo, vmrc, vmware-horizon-client, github-desktop, docker-desktop & obs-studio powertoys***

***To install the above mentioned programs run the following script***

```powershell
choco install powershell-core git vscode putty greenshot notepadplusplus winscp 7zip paint.net windirstat zoom sudo vmrc vmware-horizon-client github-desktop obs-studio docker-desktop google-drive-file-stream googlechrome curl powertoys -y

```
## Step 3: Installing some useful VScode addons 

* Restart your Powershell session 
* Run the following commands 

```powershell linenums="1"
code --install-extension ms-vscode.powershell
code --install-extension vsls-contrib.gistfs
code --install-extension ms-vscode-remote.remote-containers
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-vscode-remote.vscode-remote-extensionpack
code --install-extension GitHub.copilot
code --install-extension GitHub.vscode-pull-request-github

***To Install the above mentioned programs run the following scipt***

```
***3. Tehtävä ***

![image](https://github.com/user-attachments/assets/b310d5cd-704a-4078-9e36-a2befa3ee9bc)






