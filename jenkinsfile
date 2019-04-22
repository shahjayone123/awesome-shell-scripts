pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                sh './echo.sh'
		sh './vars.sh'
		sh './sum.sh'
            }
        }
    }
}
