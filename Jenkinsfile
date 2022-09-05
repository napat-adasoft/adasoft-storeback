pipeline {
agent any
stages {
stage('Checkout') {
steps {
git(url: 'https://github.com/napat-adasoft/adasoft-storeback.git', branch: 'production')
}
}
stage('Release') {
steps {
echo 'Ready to release etc.'
}
}
 }
}
