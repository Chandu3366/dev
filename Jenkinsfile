pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
                echo 'check out from git'
            }
        }
        stage ('build') {
            steps {
               echo 'build passed'
            }
        }
        stage ('test') {
          steps { 
             echo 'test passed'
          }
        }
        stage ('deploy') {
           steps {
             echo 'deploy successed'            
           }
        }
    }
}
