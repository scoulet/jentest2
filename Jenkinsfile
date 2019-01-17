node {
    stage('Clone'){
        checkout scm
        echo "aaaaaa"
    }
    
    stage('Deploy'){
        deploydocker = docker.build("scoulet/jendocktest")
        sh 'docker run -p 8888:5000 -e VAR="d" scoulet/jendocktest'
    }

}
