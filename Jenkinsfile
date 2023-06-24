pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'building the application... '
            }
        }
      
        stage('test') {
            steps {
                echo 'testing the application...'
            }
        }
      
        stage('deploy') {
            steps {
                echo 'deploy the application...'
            }
        }
        post{
            always{
                //sending an email out to the team about the bill condition
            }
            success{
                //only relevant if the build succeeded 
            }
            failure{
                //all the different conditions on the past block
            }
        
        }
    }
}
