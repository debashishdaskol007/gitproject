@Library('piper-lib-os') _

cloudFoundryDeploy script: this
fioriOnCloudPlatformPipeline script:this

stage('deploy') {
    cloudFoundryDeploy script: this
}
