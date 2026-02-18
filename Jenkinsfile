pipeline{
agent any

stages{

stage('clone'){
steps{
git url: 'https://github.com/pjeevan740-stack/jenkins-simple-demo.git',
branch: 'main'
}
}

stages('Run Script'){
steps{
sh 'chmod +x script.sh'
sh './script.sh'
}
}
}
}
