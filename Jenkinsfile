pipeline {
agent {
docker {
image 'centos7'
label 'w2'
}
}
stages {
stage('Clone GIT repo') {
steps {
sh 'yum install git -y'
sh 'git version'
sh 'echo satya'
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
