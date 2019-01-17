node {
    stage('Clone'){
        checkout scm
        echo "aaaaaa"
    }
    
    stage('Deploy'){
        deploydocker = docker.build("scoulet/jendocktest")
        sh 'docker run -e VAR="d" scoulet/jendocktest'
    }

}
