def returnVar() {
    echo "Hello World"
} 

node ('master') {
    stage ('Bash') {
        sh'''
        returnVar()
        '''
    }
}