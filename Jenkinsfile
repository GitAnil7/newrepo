pipeline{
    agent any
    stages {
        stage('master branch') {
            steps {
                sh 'echo "this is master branch" '
            }
        }
    stages {
        stage('dev1') {
            steps {
                sh 'echo "develpoment applicaiton" '
            }
        }
    stages {
        stage('hotfix') {
            steps {
                sh 'echo "deploy application" '
            }
        }
    }
}
