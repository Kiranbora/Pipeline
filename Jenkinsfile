pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'Build success'
            }
        }
        stage('Test'){
            steps {
                echo 'Tested success' 
            }
        }
        stage('package') { 
            steps { 
                echo 'package success'
            }
        }
        stage('Deploy') {
            steps {
            echo 'Deploy in openshift'
		}
        }
    }
}
