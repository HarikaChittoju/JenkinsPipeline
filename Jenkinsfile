pipeline{
agent {
docker{
image 'java:latest'
}
}
stages{
stage('Build'){
steps{
sh 'javac HelloWorld.java'
}
}
stage('Run'){
steps{
sh 'java HelloWorld'
}
}
}
}

