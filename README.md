## Fizz Buzz Example in Java 8 using Jenkins Pipeline to publish Cucumber Reports

### Fizz Buzz is a game where
- if the number is divisible by 3, you say Fizz
- if the number is divisible by 5, you say Buzz
- if the number is divisible by 3 & 5, you say FizzBuzz
- if neither, you say the number

### Pre-requisite
- Add `Cucumber Reports` plugin in Jenkins to use `cucumber` DSL as shown 
in the `Jenkinsfile`

docker run jenkins -p 9080:8080 -d
docker ls
docker logs -f
git remote add origin https://github.com/srikanth2687/jenkins-pipeline.git

"${mvnHome}/bin/mvn -B  clean install"