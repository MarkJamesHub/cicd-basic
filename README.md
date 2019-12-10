
# Added Gradle Wrapper to project (allow Gradle to install itself on the target)

  Install dependancies: java-1.8.0-openjdk (brew install...

  Install Gradle 6.0.1
  
    .brew install gradle

  go to repo: cd jenkinstest

  run: gradle wrapper

  exclude in .gitignore
  
    .gradle (directory)
  
  Note: gradlew is for mac/linux         gradlew.bat is for windows
  
  run: ./gradlew build
  
  
# Added a Jenkinsfile


# Added a Dockerfile

