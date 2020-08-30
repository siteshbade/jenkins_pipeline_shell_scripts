node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git url: 'https://github.com/siteshbade/jenkins_pipeline_shell_scripts.git'
   	stage 'Build'
   		bat './myBuild.bat'
   	stage 'Deploy'
   		bat './myDeployment.bat'
  
}
