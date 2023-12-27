pipeline{
    agent{
        node{
            label 'Default-node'
        }
        
    }
    triggers{
        pollSCM '*/1 * * * *'
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
