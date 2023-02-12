pipeline {
    agent any

    stages {
       
        stage('Build') {
            steps {
                sh " mvn build install package "
            }
        }
    }
}
