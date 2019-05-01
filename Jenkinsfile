pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                    powershell "& 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2017\\Community\\MSBuild\\15.0\\Bin\\MsBuild.exe' GenelProje.sln"
            }
        }
         stage('Test') {
            steps {
                echo 'Hello Test Ahmet'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Hello  Deploy Ahmet'
            }
        }
    }
}