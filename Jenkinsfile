pipeline
{
stages {
        stage('build') {
            steps {
                sh 'bandit -r DSVPWA-main -f html -o dsvpwaa.html'
            }
        }
    }
}
