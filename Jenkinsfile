pipeline {
    agent any
    stages {
        stage ("Welcome"){
            steps {
                echo "Welcome"
            }
        }
        stage ("Git Checkout"){
            steps {
                git branch: 'main', url: 'https://github.com/ashishmishra17/newrepo.git'
            }
        }
    }
}
