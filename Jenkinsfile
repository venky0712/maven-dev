pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
                echo 'Hello Poll SCM'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}     
