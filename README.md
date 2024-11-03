1. Use settings.xml to add the local jar to dependencies
2. Don`t forget to change default login and path
3. Be aware to push your credentials to the GitHub

! You can use install-plugin with command
"mvn install:install-file -DgroupId=com.javarush -DartifactId=desktop-game-engine -Dversion=1.0 -Dfile=lib/desktop-game-engine.jar -Dpackaging=jar -DgeneratePom=true "