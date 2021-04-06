pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh '''
                #!/bin/bash
                echo 'Hello World'
                
                cd /var/lib/jenkins/workspace/'c pipeline project'
                make
                ./ABC.exe
                echo "test webhook"
                rm -rf *.o ABC.exe
                '''
            }
        }
    }
}
