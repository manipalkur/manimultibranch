 properties([[$class: 'GithubProjectProperty',
                 displayName: '',
                 projectUrlStr: 'https://github.com/manipalkur/manimultibranch.git/'], 
                 pipelineTriggers([githubPush()])])

pipeline {
    agent any
   
    stages {
        stage('Example') {
            steps { 
                echo 'Hello World'
            }
        }
    }
}
