pipeline{
agent any
stages
{
stage('Build')
{
steps{
echo "Building the Project..."
bat "mvn clean"
}
}
stage('Deploy')
{
steps{
echo "Deploying the Project..."
bat "mvn test"
}
}
stage('Test')
{
steps{
echo "Testing the Project..."
bat "mvn test"
}
}
stage('Release')
{
steps{
echo "Releasing the Project..."
bat "mvn release"
}
}
}
}
