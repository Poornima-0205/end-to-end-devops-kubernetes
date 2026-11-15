cat > Jenkinsfile <<'EOF'
pipeline {
    agent any

    tools {
        jdk 'Java-21'
        maven 'Maven-3'
    }

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Java application with Maven'
            }
        }

        stage('Test') {
            steps {
                echo 'Running application tests'
            }
        }
    }
}
EOF
