pipeline {
    agent any
    tools {
        maven 'maven'
    }
    
    stages {
        stage('Checkout') {
            step {
                git url: "https://github.com/ndzohdong/spring-petclinic-microservices.git", branch: "*"
            }
        }
    }
}