 properties([[$class: 'GithubProjectProperty',
                 displayName: '',
                 projectUrlStr: 'https://github.com/manipalkur/manimultibranch.git/'], 
                 pipelineTriggers([githubPush()])])

pipeline {
    agent any
   /// added a comment just to test 
    stages {
        stage('Example') {
            steps { 
                echo 'Hello World'
            }
        }
    }
}
