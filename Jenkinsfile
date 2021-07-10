pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Anshul from LevelUp360'
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
                        echo "Deploying into Staging_Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying into Production_Area"
                  }
            }
      }
}
