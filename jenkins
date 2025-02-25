pipeline
{
agent any
stages{
stage('clone')
steps{
git 'https://github.com/RamakrishnaTanam/aabbccdd.git'
}
}
stage('build')
{
steps{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
