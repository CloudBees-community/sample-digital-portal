node () {
     stage("Build") {
         checkout scm

         sh """

         # WORKAROUND TIGER-3084
         unset MAVEN_CONFIG

         ./mvnw --batch-mode --show-version clean package
         """
     }
 }