pipeline
{
        agent any
        stages {
        stage('Bandit') {
            steps {
                sh "bandit -r DSVPWA-main -f html -o dsvpwa3.html"
            }
        }
        stage('Semgrep'){
                steps{
                        sh "semgrep scan C:\Users\Hp\Desktop\Sast\DSVPWA-main\DSVPWA-main"
                }
        }               
    }
}
