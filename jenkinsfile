pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh '''
                #!/bin/bash
                echo 'Hello World'
                
                cd test
                make
                ABC.exe
                rm -rf *.o ABC.exe
                '''
            }
        }
    }
}
