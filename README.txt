mvn clean: deletes the /target folder. So, the same result for both commands.
mvn package: Converts your .java source code into a .jar/.war file and puts it into the /target folder.
mvn install: First, it does a package(!). Then it takes that .jar/.war file and puts it into your local Maven repository, which lives in ~/.m2/repository.


For clean : mvn clean
For compile : mvn compile
For test : mvn test
For creating jar/war package : mvn package
For install : mvn install
