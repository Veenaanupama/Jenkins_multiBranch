node('built-in') 
{
    stage('Continuous Download_project') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_project') 
	{
    sh label: '', script: 'mvn package'
	}
}   
