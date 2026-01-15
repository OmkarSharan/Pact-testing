# Pact-testing

1. Pull the project
2. to build run command ->  ./gradlew clean build
3. to run the test -> ./gradlew clean test


Steps to create the issue : 

1. Run the test class : AppTest first. You check the contract and focus on the authorization header part.
2. Run the test case : UserTest, you will see the existing interaction from step one get changed (Authorization header part)
