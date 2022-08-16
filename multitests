pipeline {

    agent any

    stages {
        stage('Test1') {

            when {
        branch 'master'
      }
            steps {
                echo "this is my stage test1"
            }
        }

        stage('Test2') {

            when {
        branch 'master'
      }
            steps {
                echo "this is my stage test2"
            }
        }
    }
}
