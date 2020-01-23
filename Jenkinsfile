pipeline {
    agent any 
    parameters {
        string( name: 'pkgName', description: 'Provide the Package Name?', defaultValue: 'httpd' )
        choice( name: 'pkginstall_Confirmation', choices: "-y \n -n \n yes \n no ", description: 'Confirm?')
        }
    stages {
        stage('Test')
        {
            steps 
            {
            echo "${params.pkgName}"
			echo "${params.pkginstall_Confirmation}"
            }
		}
    }
}
