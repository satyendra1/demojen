pipeline {
agent {
docker {
image 'centos:latest'
label 'w2'
}
}
stages {
stage('Clone GIT repo') {
steps {
sh 'git version'
}
}
stage('Build') {
steps {
sh 'echo "Building the code"'
}
}
stage('Deploy') {
steps {
sh 'echo "Deploying the software on Kubernetes"'
}
}
}
}
