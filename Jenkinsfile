node{

stage('Checkout')
{
    
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '797acaac-7307-4182-94aa-6a1b7349b6de', url: 'https://github.com/Trivedi10/GitPracticeRepo.git']]])
}

stage('Build')
{
    echo "Building Stage"
    
}

stage ('Deploy')
{
    
    echo "Deploying Stage"
    
}
}
