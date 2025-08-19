pipeline{
 agent any
stages{
 stage('checkout code'){
steps{
git branch: 'main', url: 'https://github.com/srivallikottamasu/test'
}
 }
stage('build'){
steps{
sh 'echo "building the app"'
}
}
stage('test'){
steps{
sh'echo "testing the app"'
}
}
stage('deploy'){
steps{
sh'echo "deploying the app"'
}
}
}
}
