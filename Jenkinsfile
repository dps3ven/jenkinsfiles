def returnVar(String a, String b) {
    ls /tmp
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
