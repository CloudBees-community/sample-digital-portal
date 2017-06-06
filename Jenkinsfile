node ("maven-jdk-8") {
     stage("Build") {
         checkout scm
         sh 'echo "pwd: $(pwd)"'
         sh 'env'
         sh """
         # WORKAROUND TIGER-3084
         unset MAVEN_CONFIG
         
         ./mvnw --batch-mode --show-version --debug clean package
         """
         // sh "mvn --batch-mode --show-version --debug clean package"
     }
 }