pipeline {
    agent any

    stages {
        stage("build") {
            steps{
            sh "df -Th"
            sh "minikube start"
            sh "kubectl get pod --all-namespaces -o wide"
            }
        }
    }
}