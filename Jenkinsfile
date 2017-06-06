node {
    stage("Build") {
        checkout scm
        sh 'echo "pwd: $(pwd)"'
        sh 'env'
        sh "./mvnw --batch-mode --show-version clean package"
    }
}