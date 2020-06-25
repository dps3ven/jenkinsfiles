def returnVar(String a) {
    sh'''
    gcloud config configurations a
    '''
} 

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
