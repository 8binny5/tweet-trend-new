pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/8binny5/tweet-trend-new.git'
            }
        }
    }
}