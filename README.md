# Power Apps Component Framework - Dev Containers

This is a template repo to enable anyone to create new repos with Dev Container config setup. With Dev Containers, you can develop entirely inside GitHub Codespaces. The biggest advantage is that you don't need all the dependencies like VSCode, .NET Framework, Node JS all installed on your local machine. Everything you need is right inside the browser.

# Usage
 
 1. Create a new repo from this template by clicking the _Use this Template_ button
 2. After the template is instantiated, you can open the repo in Codespaces by clicking _Code -> Open with Codespaces_
 3. After you are in Codespaces create a new folder called _src_ for storing PCF component
 4. PCF Builder extension is installed on the Dev Container. So, you can use it to do your PCF Component build/deploy
 5. After the _npm install_ completes, run _./fix.ps1_ script, so that you can run the PCF Test Harness

Port mapping to 8081 is setup, so you would be able to test and debug using Test Harness exactly like how you do it in your local machine


# Known Issue

The very first time you run something from PCF Builder, the path would be the folder with README.md. This would cause _pac_ to complain that .gitignore already exists. So, you need to navigate into _src_ folder and try this again. Make sure that you are in the PCF Builder terminal window when you do this.