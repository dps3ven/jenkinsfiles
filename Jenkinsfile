def returnVar(String a, String b) {
    sh "ls /tmp"
    sh "gcloud $a configurations $b"
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
