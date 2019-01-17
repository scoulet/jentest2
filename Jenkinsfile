node {
    stage('Clone'){
        checkout scm
        echo "aaaaaa"
    }
    docker.image('node:7-alpine').inside {
        stage('Test')
        sh 'node --version'
    }
}
