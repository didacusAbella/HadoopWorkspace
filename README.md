# Instuction to compile

1. `git clone` the project
2. Open __pom.xml__
3. Search the `<property>` tag and modify the tags __`<hadoop-version>`__ and __`<main>`__ to adapt to your maven version and main class
4. Code and Build the new project with an IDE or launch `mvn compile` from command-line 
5. Generate Jar with an IDE or launch `mvn package`. The output is in __target__ directory
5. Launch the jar normally with `hadoop jar *jar-path*`
