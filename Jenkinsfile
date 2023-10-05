pipeline {
    agent any

    stages {
        stage('Hello') {
            environment {
                jeya_id = credentials('secrettext1')
            }
            steps {
                echo "credential is ${jeya_id} "
            }
        }
    }
}
