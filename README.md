# DadsTaxi
A fictional taxi

## Samples and links
- [snake line](https://azuremapscodesamples.azurewebsites.net/index.html?sample=Animate%20a%20snakeline)

## Verify page load from remote locations using Azure Functions
- Create a *linux* Azure Function using azure functions, enable "SCM Do Build During Deployment" in the Azure functions VSCode settings then follow this to screenshot your site https://anthonychu.ca/post/azure-functions-headless-chromium-puppeteer-playwright/
  Playground for Puppeteer - https://try-puppeteer.appspot.com/
- Modify DOM in Puppeteer - https://stackoverflow.com/a/48513690
- How to pass variable into JS eval function - https://stackoverflow.com/questions/46088351/how-can-i-pass-variable-into-an-evaluate-function

## Healthcheck config
We look for a file named /public/healthcheck.txt - when connected to other resoures such as a DB then the healthcheck should be deep enough to verify this but txt works for now
- https://azure.github.io/AppService/2016/11/17/URL-Authorization-Rules.html
- https://social.msdn.microsoft.com/Forums/en-US/80bad646-a8ec-411b-8549-7446e419f167/azure-ad-authentication?forum=AzureFunctions