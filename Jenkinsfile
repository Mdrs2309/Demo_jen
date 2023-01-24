pipeline
{
        agent any
        stages {
        stage('build') {
            steps {
                sh "bandit -r DSVPWA-main -f html -o dsvpwa3.html"
            }
        }
    }
}
