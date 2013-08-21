Requires a custom built Jar file which can be acquired from:

  https://github.com/TakaGoto/ttt_java/tree/master/lib

to run tests:

  git clone https://github.com/TakaGoto/java_console_ttt.git

  cd java_console_ttt

  mvn install:install-file -Dfile=/your/path/to/TicTacTac.jar -DgroupId=TicTacToe -DartifactId=TicTacToeJar -Dversion=1.0.0 -Dpackaging=jar

  mvn test
