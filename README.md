
# Add Gradle Wrapper to project

  Install dependancies: java-1.8.0-openjdk
  
    brew install...

  Install Gradle 6.0.1
  
    brew install gradle

  go to repo
  
    cd jenkinstest

  initialise the repo

    gradle init
    
    or
    
    gradle wrapper

  exclude gradle dir in .gitignore
  
    vi .gitignore
    i
    .gradle
    :wq!
  
  Note: gradlew is for mac/linux         gradlew.bat is for windows
  
  Run a gradle build to download files for the firsttime
  
    ./gradlew init
  
  Configure build.gradle file
  
    vi build.gradle
    i
    <paste gradle.build.template content here>
    :wq!
  
# Add Jenkinsfile to Project


# Add Dockerfile to Project

