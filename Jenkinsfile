node('any') {
stage 'build'
       openshiftBuild(buildConfig: 'back-end', showBuildLogs: 'true')
       stage 'deploy'
       openshiftDeploy(deploymentConfig: 'back-end')
}