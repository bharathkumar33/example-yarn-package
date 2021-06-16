pipeline{
    agent any
    stages {
        stage("run frontend"){
            steps {
                echo "executing yarn"
                nodejs("Node"){
                    sh 'yarn install'
                    sh 'yarn run test'
                }
            }
        }
    }
}