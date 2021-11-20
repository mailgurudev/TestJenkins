pipeline {
    agent {
        label 'master'
    }
    triggers {
        cron('0 14 * * 1-5')
    }
    
    stages {
         stage('git stash') {
            steps {
                sh '(pwd)'
            }
        }
        
    }
}
