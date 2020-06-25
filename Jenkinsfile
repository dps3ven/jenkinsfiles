pipeline {
    agent {
        label 'master'
    }
    stages {
        stage ('Bash') {
            step {
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