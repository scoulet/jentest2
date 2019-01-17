node {
    stage('Clone'){
        checkout scm
        echo "aaaaaa"
    }
    
    stage('Front End'){
        docker.image('maven:3-alpine').inside {
            sh 'mvn --version   
        }
    }
    
    stage('Front End') {
        docker.image('node:7-alpine').inside {
            sh 'node --version'
        }
    }
}
