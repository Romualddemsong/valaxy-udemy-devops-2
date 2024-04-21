pipeline {
    agent {
        node{
            label 'ubuntu'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/Romualddemsong/valaxy-udemy-devops-2.git'
            }
        }
    }
}
