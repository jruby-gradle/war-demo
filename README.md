# jruby-gradle-war-plugin demos

In this project:

 * **executable-war** - A web archive which can run like a command line
   application (`java -jar my.war list-commands`)  or deployed into a servlet container.
 * **runnable-war** - A web archive which can be self-running, i.e. `java -jar
   my.war` will spin up an embedded web server. Can also be deployed to a
   servlet container
 * **simple-war** - A non-runnable, non-executable, simple web archive to be
   deployed in a servlet container
