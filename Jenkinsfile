pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'We are Starting the Init steps'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project Step 5'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
