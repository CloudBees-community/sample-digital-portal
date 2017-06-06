node {
    stage("Build") {
        sh 'echo "pwd: $(pwd)"'
        sh 'env'
        sh "./mvnw clean package"
    }
}