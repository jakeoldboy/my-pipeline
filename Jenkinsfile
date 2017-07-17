#!groovy

node('master') {

    stage('Clean Workspace') {
        // Delete workspace
        echo 'stage: Clean Workspace - step deleteDir()'
//      deleteDir()
    }

    stage('Checkout') {
        // Checkout Code
        echo 'stage: Checkout - step checkout scm'
//      checkout scm
    }

    stage('Build') {
    
         echo 'stage: Build'

        // Update build name
//        getCommitRevision()
//        currentBuild.displayName = "#" + env.BUILD_NUMBER + "-" + env.GITHASH.substring(0, 7)
//        def localdisplayName = env.BUILD_NUMBER + "-" + env.GITHASH.substring(0, 7)
        // Build
//        setJavaHomeOnPath()
//        sh "./gradlew clean assemble -x test --console=plain --no-daemon --stacktrace --rerun-tasks"

        // Archive files
//        step([$class: 'ArtifactArchiver', artifacts: 'build/**/*.jar, manifests/manifest*.yml', , fingerprint: true])

//        // Stash artifacts for later use in this run
//        stash includes: 'build/**/*.jar, manifests/manifest*.yml', name: 'artifacts'
    }

}
