node {
    def applicationTitle = 'Learnign Project';

    stage('Checkout Code') {
        git branch: 'master', url: 'https://github.com/atinsingh/devops-project1.git'
    }

    stage('Copy HTML') {
        sh 'cp index.html /var/www/html/'
    }
    stage('Copy Images') {
        sh 'cp -r images/ /var/www/html/'
    }

    stage('Notify Email') {
        sh 'Sending email'
    }
}