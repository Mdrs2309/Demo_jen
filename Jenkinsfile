pipeline
{
        agent any
        stages {
         stage('Build') {
            steps {
                git 'https://github.com/Mdrs2309/Demo_jen.git'
            }
            }
        stage('Bandit') {
            steps {
                sh "bandit -r DSVPWA-main -f html -o dsvpwa3.html"
            }
        }
        stage('Semgrep'){
                steps{
                        sh "semgrep --config=auto "
                }
        }               
    }
}
