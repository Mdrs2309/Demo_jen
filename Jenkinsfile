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
                sh "bandit -r \ProgramData\Jenkins\.jenkins\DSVPWA-main -f html -o \Users\Hp\Desktop\Sastdsvpwa3.html"
            }
        }
        stage('Semgrep'){
                steps{
                        sh "semgrep --config=auto "
                }
        }               
    }
}
