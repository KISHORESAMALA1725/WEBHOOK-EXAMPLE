pipeline {
    agent {
        label 'java-save'
    }
    stages {
        stage ('this is build: maven stage') {
            echo " ********* ********"
        }
    }
    post{
        success {
            echo "this stage will execute then job is success"
        }
        failure {
            echo "this stage will execute then job is failure"
        }
        always {
            echo "this stage will execute in any condition"
        }        
    }
}
