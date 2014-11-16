Here is the source code and project directory for the EventListing
Android app I made for my Clojure + Android [Tutorial](https://github.com/krisc/events/blob/master/tutorial.md).

Adding Infomation (ART Support Version)
----------
1. May you need set :sdk-path on project.clj, when error of ":sdk-path is nil".

2. You need JDK 1.7 to compile files with neko library (current version)

**OSX (comand line):**

    $ JAVA_HOME=$(/usr/libexec/java_home -v 1.7) lein droid doall


