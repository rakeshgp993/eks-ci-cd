// @Library('jenkins-shared-lib')
library "jenkins-shared-lib@main"

node {
pipelineHelper.pipelineStart()

pipelineHelper.checkout()

 stage('hello world') {
     echo 'Hello world'
     sayHello("rakesh")
 }

 pipelineHelper.pipelineFinish()
}