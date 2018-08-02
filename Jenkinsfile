pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
               cat deployment.yaml
            }
        }
        stage('Test'){
            steps {
                ls 
            }
        }
        stage('Deploy') {
            steps {
                cat service.yaml
            }
        }
    }
}
