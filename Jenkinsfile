node {
    stage("Build") {
        sh 'echo "pwd: $(pwd)"'
        sh 'env'
        sh 'ls -al $WORKSPACE'
        sh "$WORKSPACE./mvnw clean package"
    }
}