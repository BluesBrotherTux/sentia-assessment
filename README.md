# sentia-assessment
My job application repository

Files:
- deploy.ps1, deploy.sh, deployer.rb, DeploymentHelper.cs are provided
  by Azure automation export
- template.json, parameters.json are generated by the export and
  altered to meet the assessment used by the Azure deploy scripts
- restrictResourceTypesPolicy.json, restrictResourceTypesAssignement.json
  failed attempts to create the policy
- computePolicyDefinition.json.txt, networkPolicyDefinition.json.txt,
  storagePolicyDefinition.json.txt contain .json body examples used 
  within the Azure portal
- .json body used for the REST API to implement the policy initiative

https://github.com/BluesBrotherTux/sentia-assessment/wiki includes the
roadmap for the assessment.

Run one of the MS deployment scripts to create the resourceGroup
meeting the objective of the assessment. Connect to your Azure 
subscription. Enter <name> and <location>

Example:
Open Windows powershell. Go to directory containing deployment scripts
and .json files and run from the command shell:
.\deploy.ps1

