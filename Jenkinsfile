properties([[$class: 'GithubProjectProperty', 
           displayName: '',
           projectUrlStr: 'https://github.com/Demo-Project333/Rep1.git/'], 
           pipelineTriggers([upstream('Demo-Teja'),
            githubPush()])])

pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo " This is Build Stagee"
            }
        }
        stage('Test'){
            steps {
                echo "This is a Test Stagee" 
            }
        }
        stage('Deploy') {
            steps {
                echo "This is a Deploy Stage"
            }
        }
    }
}
