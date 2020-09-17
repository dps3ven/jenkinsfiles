pipeline {
    agent any
    stages("Test") {
        stage("Echo") {
            steps {
                echo "This is a test"
            }
        }
        stage("Checkout") {
            git
            url: 'https://github.com/dps3ven/jenkinsfiles.git'
            branch: 'master'
        }
    }
}