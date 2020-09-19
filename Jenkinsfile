pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git branch: 'main', url: 'https://github.com/awstrainingsept/spring-petclinic.git'
            }
        }
    stage("Maven Build"){
            steps{
                sh "mvn clean test"
            }
        }
}
}
