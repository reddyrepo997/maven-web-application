def workspace
node
{
  
      stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'b3027d50-1e47-4b78-98a8-85e83d9db0f1', url: 'https://github.com/reddyrepo997/maven-web-application.git']]])
        workspace=pwd()
    }
    
    stage('Build')
    {
        echo "Building the job"
    }
    stage('test')
    {
        echo "Testing the job"
    }
    stage('Deploy')
    {
        echo "Deployimg the code"
    }
}  
