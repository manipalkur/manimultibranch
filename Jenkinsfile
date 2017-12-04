pipeline {
    agent any
    properties([[$class: 'GithubProjectProperty',
                 displayName: '',
                 projectUrlStr: 'https://github.com/manipalkur/manimultibranch.git/'], 
                 pipelineTriggers([githubPush()])])
    stages {
        stage('Example') {
            steps { 
                echo 'Hello World'
            }
        }
    }
}
