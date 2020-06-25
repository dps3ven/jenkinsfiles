pipeline {
    agent master
    
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