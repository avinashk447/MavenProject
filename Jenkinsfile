node{
stage('scm checkout from git'){
git 'https://github.com/avinashk447/MavenProject'
}
stage ('compile-package')
{
//get maven home path
def mvnHome = tool name: 'maven', type: 'maven'
  sh "${mvnHome}\C:\Program Files (x86)\Jenkins\jobs\mvn package"

}


}
