pipeline {
    agent {
        label 'master'
    }
    stages {
        stage ('Bash') {
            script {
                returnVar("list")
            }
        }
    }
}

def returnVar(String a) {
    sh'''
    gcloud config configurations a
    '''
} 