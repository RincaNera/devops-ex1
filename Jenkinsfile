pipeline {
    agent any
    triggers {
        pollSCM('*/2 * * * *')
    }
    stages {
        stage('HelloWorld') {
            steps {
                echo 'AYAYA....'
            }
        }
    }
}
