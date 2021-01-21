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
                changeset '*.java'
            }
            
            steps {
                echo "Yes, commit files contain Java files"
            }
        }
    }
}
