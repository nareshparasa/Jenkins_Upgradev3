pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, This is Ram Naresh Parasa'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy into Production') {
                  steps {
                        echo "Deploying into Production Area"
                  }
            }
      }
}