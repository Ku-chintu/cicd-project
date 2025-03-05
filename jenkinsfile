pipeline {
    agent any

    stages {
    //   stage('clone') {
    //      steps {
    //      // git branch: 'main', url: 'https://github.com/Ku-chintu/cicd-project.git'
    //     }
    //  }
        stage('init') {
            steps {
                sh 'terraform init'
            }
        }
         stage('plan') {
            steps {
                sh 'terraform plan'
            }
        }
    }
}
