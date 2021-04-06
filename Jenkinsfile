pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh '''
                #!/bin/bash
                echo 'Hello World'
                
                cd 'c pipeline project'
                make
                ABC.exe
                rm -rf *.o ABC.exe
                '''
            }
        }
    }
}
