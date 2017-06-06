node {
    stage("Build") {
        sh 'echo "pwd: $(pwd)"'
        sh 'env'
        sh "$WORKSPACE./mvnw clean package"
    }
}