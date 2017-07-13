node {
  stage 'Checkout'
    git url: 'https://github.com/rajivreddy/Faker.git'
  stage "install dependencies using composer"
    sh '/usr/local/bin/composer install'
  stage "list all files and folders"
    sh 'ls -lthr'
  stage 'Running unit test cases'
   		sh './vendor/bin/phpunit'
}
