pipeline{
    agent{
        node{
            label 'Default-node'
        }
        
    }
    triggers{
        pollSCM '* * * * *'
    }
    stages{
        stage('Build'){
            steps {
                echo "Bulding .."
                sh '''
                echo "Doing bulding stuff.."
                '''
            }
        }
    }
}
