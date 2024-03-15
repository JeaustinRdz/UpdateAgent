Steps to implement the pipeline

1: Create a personal access token https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows#create-a-pat

2: Create a new pipeline and Copy and paste the content of the yml file

3: Create a new Variable with the name ADO_PAT and the value the token created in the step 1 in the variable secction of the pipelines, make sure to enable the option Keep this value secret
![image](https://github.com/JeaustinRdz/UpdateAgent/assets/163601125/1152d1c8-ed67-47cc-9663-26fc8fb73d52)

4: Change the Org and PoolID in the yml

How to schedule a pipeline https://learn.microsoft.com/en-us/azure/devops/pipelines/process/scheduled-triggers?view=azure-devops&tabs=yaml
