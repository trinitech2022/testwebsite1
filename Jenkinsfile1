pipeline {

       agent any

       stages {

              stage('Build') {

                     steps {

                            echo 'Running build automation'

                             sh './gradlew build --no-daemon'

                             archiveArtifacts artifacts: 'trinitech-web/website1.zip'

      }

}



}



}
