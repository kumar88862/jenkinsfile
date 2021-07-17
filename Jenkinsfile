pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "python"
            }
        }
    }
    post{
        failure{
            echo "failed"
        
        }
    
    }
}
