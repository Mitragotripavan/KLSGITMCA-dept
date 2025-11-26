node {
    stage('Welcome') {
        echo '🎉 Welcome Students! 🎉'
        echo 'This build was triggered from GitHub!'
    }
    
    stage('Checkout Code') {
        echo 'Downloading code from GitHub...'
        checkout scm
    }
    
    stage('List Files') {
        sh 'ls -la'
        echo 'These are all files from GitHub repository'
    }
    
    stage('Build Info') {
        echo "Build Number: ${env.BUILD_NUMBER}"
        echo "Git Branch: ${env.BRANCH_NAME}"
        echo "This is so cool! 🤩"
    }
}
