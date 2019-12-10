
# Add Gradle Wrapper to project

  Install dependancies: java-1.8.0-openjdk
  
    brew install...

  Install Gradle 6.0.1
  
    brew install gradle

  go to repo
  
    cd jenkinstest

  initialise the repo

    gradle wrapper

  exclude gradle dir in .gitignore
  
    vi .gitignore
    i
    .gradle
    :wq!
  
  Note: gradlew is for mac/linux         gradlew.bat is for windows
  
  Run a gradle build to download files for the firsttime
  
    ./gradlew build
  
  Configure build.gradle file
  
    vi .gitignore
    i
    <paste gradle-build content here>
    :wq!
  
# Added a Jenkinsfile


# Added a Dockerfile

