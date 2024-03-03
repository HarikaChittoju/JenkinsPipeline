pipeline{
agent {
docker{
image 'maven:latest'
}
}
stages{
stage('Build'){
steps{
sh 'mvn compile'
}
}
stage('Run'){
steps{
sh 'java -cp .HelloWorld'
}
}
}
}

