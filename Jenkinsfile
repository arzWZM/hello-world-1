pipeline {
    agent any
    stages {
        stage("PerlFiles") {
            when {
                changeset '*.pl'
            }
            
            steps {
                echo "Yes, commit files contain perl files"
            }
        }
        
        stage ("Java") {
            when {
                changeset '*.xml'
            }
            
            steps {
                echo "Yes, commit files contain XML files"
            }
        }
    }
}
