node ("maven-jdk-8") {
     stage("Build") {
         checkout scm
         sh 'echo "pwd: $(pwd)"'
         sh 'env'
         // sh "./mvnw --batch-mode --show-version --debug clean package"
         sh "mvn --batch-mode --show-version --debug clean package"
     }
 }