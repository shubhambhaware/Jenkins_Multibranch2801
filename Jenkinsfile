node('built-in') 
{
    stage('Continuous Download Mater') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('Continuous Build Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
