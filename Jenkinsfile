pipeline {
   ageny any
         stages {
             stage ('---clean---') {
                 step {
                 bat "mvn clean"
                 }
             }
         stage ('---test---') {
              step {
                  bat "mvn test"
                 }
             }
          stage('---deploy---') {
                   step {
                        bat "mvn package"
                      }
                  }
          }
}
