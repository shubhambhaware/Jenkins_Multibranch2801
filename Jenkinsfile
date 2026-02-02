node('built-in') 
{
    stage('Continuous Download lones') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('Continuous Build lones') 
	{
    sh label: '', script: 'mvn package'
	}
}
