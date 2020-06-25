def returnVar(String a, String b) {
    echo'''
    gcloud a configurations b
    '''
} 

pipeline {
    agent {
        label 'master'
    }
    stages {
        stage ('Bash') {
            steps {
                returnVar("config","list")
            }
        }
    }
}
