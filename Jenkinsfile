pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat '"C:\\Windows\\System32\\cmd.exe" /c python --version'
            }
        }

        stage('stage2') {
            steps {
                bat '"C:\\Windows\\System32\\cmd.exe" /c python mani.py %x_value% %y_value%'
            }
        }
    }
}