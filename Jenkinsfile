pipeline {
agent {
docker { image 'maven:3.5.2'
args '-v $HOME/.m2:/root/.m2'
}
}
stages {
stage('Build') {
steps {
sh 'echo "test"'
}
}
}
}  
