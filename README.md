Now we're ready to generate your uberjar:

    $ lein uberjar
    Compiling my.stuff
    Compilation succeeded.
    Created /home/phil/src/leiningen/my-stuff/target/my-stuff-0.1.0-SNAPSHOT.jar
    Including my-stuff-0.1.0-SNAPSHOT.jar
    Including clj-http-0.4.1.jar
    Including clojure-1.3.0.jar
    Including lucene-core-3.0.2.jar
    Created /home/phil/src/leiningen/my-stuff/target/my-stuff-0.1.0-SNAPSHOT-standalone.jar

This creates a single jar file that contains the contents of all your