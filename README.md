# KeyVaultReferencesARMTemplate
Creation of Azure Function App, Key Vault, and Storage Account.  All in one template adding secrets to Function App App Setting References.
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FRocco5689%2FKeyVaultReferencesARMTemplate%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Rocco5689/KeyVaultReferencesARMTemplate/master/deploytoazure.png"/>
</a>

## This ARM Template will create following resources
- App Service Plan
- Storage Account
- Function App
- Key Vault

This ARM Template inputs secrets into the Key Vault, adds the necessary access policy for the Function App in attaining the secret from Key Vault, and finally adds the secret to the Function App
