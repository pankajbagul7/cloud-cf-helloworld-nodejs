@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
     stage('build') {
        echo "starting stage build"
        mtaBuild script: this
        echo "end of stage build"
    }
    
    
    
}
