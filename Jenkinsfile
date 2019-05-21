node{
stage('SCM Checkout'){
git 'https://github.com/sureshkumarsriraman/maven_Project.git'
}
stage('Compile-Package'){
def mvnHome= tool name: '', type: 'maven'
sh "${mvnHome}/bin/mvn package"
 // sh "mvn clean install"
}
}
