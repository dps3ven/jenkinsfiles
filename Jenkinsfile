pipeline {
    agent any
    
    stages('Begin') {
        stage ('Gcloud') {
            steps {
                sh'''
                gcloud config configurations list
                '''
            }
        }
    }
}