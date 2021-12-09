pipeline {
    agent any
    stages {
        stage ('jenkinsfile clone ') {
            steps {
                git url: "git@github.com:GauravGirase/repo_with_jenkinsfile.git", branch:"main"  
                sh "README.md"
            }   
            
        }
    }
}
