pipeline {
    agent any
    stages("Test") {
        stage("Echo") {
            steps {
                echo "This is a test"
            }
        }
        stage('Checkout') {
            steps {
                git branch: 'master',
                url: 'https://github.com/dps3ven/jenkinsfiles.git'
            }
        }
        stage('Run') {
            steps {
                sh """
                ls
                chmod +x bash.sh
                """
            }
        }
    }
}