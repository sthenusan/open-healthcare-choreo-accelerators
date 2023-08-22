# open-healthcare-choreo-accelerators
Open Healthcare Choreo Accelerators for Patient Matching

Deploying the Patient Matching Accelerator on Choreo

1. Create a component in Choreo by pointing the Patient Matching accelerator's patient-matching-api branch. For more details on creating components using Github, please refer https://wso2.com/choreo/docs/develop-components/develop-components-with-git/.

2. Once the component is created, add the following environment variables. Please refer https://wso2.com/choreo/docs/devops-and-ci-cd/manage-configurations-and-secrets/#apply-environment-variables-to-your-container to add environment variables.

fhirpaths - Fhirpaths to be used for patient matching.
masterPatientIndexColumnNames - Column names of the master patient index table.
masterPatientIndexTableName - Name of the master patient index table.
masterPatientIndexHost - Host of the master patient index database. 
masterPatientIndexPort - Port of the master patient index database. 
masterPatientIndexDb - Name of the master patient index database. 
masterPatientIndexDbUser - Username of the master patient index database. 
masterPatientIndexDbPassword - Password of the master patient index database.

3. Deploy and test the component.