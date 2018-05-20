# azure-functions-beta-template
For deploying azure functions v2 beta.

# To Run
- `Connect-AzureRmAccount`
- `New-AzureRmResourceGroupDeployment -Name iqans-test-fun
c1 -ResourceGroupName iqans-func1 -TemplateFile .\template.json -TemplateParameterFile .\parameters.json -nameFromTempla
te iqans-test-func1`