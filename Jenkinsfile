pipeline {
    agent any

    stages {
        stage('Pull code') {
            steps {
               checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'cb955939-dc87-41c7-aca9-d3f12e62929e', url: 'git@github.com:zhuorenqiao/next-test.git']]])
            }
        }
    }
}
