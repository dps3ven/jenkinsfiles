def returnVar(String a) {
    echo'''
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
