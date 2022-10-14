# Power Apps Component Framework - Dev Containers

This is a template repo to enable anyone to create new PCF component repos with Dev Container config setup. With Dev Containers, you can develop entirely inside GitHub Codespaces. The biggest advantage is that you don't need all the dependencies like VSCode, .NET Framework, Node JS all installed on your local machine. Everything you need is right inside the browser.

# Usage
 
 1. Create a new repo from this template by clicking the _Use this Template_ button
 2. After the template has created your repo, you can open the repo in Codespaces by clicking _Code -> Open with Codespaces_
 3. After you are in Codespaces, create a new folder called _src_ for storing PCF component
 4. PCF Builder and Power Platform Tools extensions are installed on the Dev Container. So, you can use it to do your PCF Component build/deploy
 
Port mapping to 8081 is setup, so you would be able to test and debug using Test Harness exactly like how you do it in your local machine


# Known Issues

1. pac command is only available after the Power Platform CLI extension is installed. So, please wait for the confirmation message before running pac inside bash.
2. Reloading does not seem to work inside Dev Containers inside VSCode. But, it does work inside GitHub Codespaces
