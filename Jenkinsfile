@Library('jenkins_shared_library') _
def configMap = [
    PROJECT = "roboshop",
    COMPONENT = "user"
]
if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
    nodejsEKSPipeline(configMap)
}
else {
    echo 'Please Proceed with PROD Access'
}