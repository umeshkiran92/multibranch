node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/umeshkiran92/multibranch.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
  }
