pipeline{
agent {
docker{
image 'openjdk:11'
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

