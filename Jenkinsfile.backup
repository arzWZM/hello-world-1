pipeline {
    agent any
    stages {
        stage("Build Stage") {
            when {
                changelog 'Build'
            }
            
            steps {
                echo "Yes, change log contains hello message.."
            }
        }
        
        stage ("Deploy stage") {
            when {
                changelog 'Deploy'
            }
            
            steps {
                echo "This stage will use for Deploy"
            }
        }
    }
}
