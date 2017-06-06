node {
    stage("Build") {
        checkout scm
        sh 'echo "pwd: $(pwd)"'
        sh 'env'
        sh 'ls -al $WORKSPACE'
        sh "./mvnw clean package"
    }
}