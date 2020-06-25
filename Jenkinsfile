pipeline {
    agent {
        label 'master'
    }
    stages {
        stage ('Bash') {
            steps {
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