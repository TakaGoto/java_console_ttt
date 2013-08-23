Requires a custom built Jar file TicTacToe.jar which is inside the lib directory in this repo

to run tests:

Add jar file

  mvn install:install-file -Dfile=/your/path/to/lib/TicTacTac.jar -DgroupId=TicTacToe -DartifactId=TicTacToeJar -Dversion=1.0.0 -Dpackaging=jar

  mvn test

To run, from root:

java -cp out/artifacts/java_console_ui_jar/java_console_ui.jar com.company.Main
