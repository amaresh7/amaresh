pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
                git 'https://github.com/amaresh7/amaresh.git'
            }
          }
        }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
