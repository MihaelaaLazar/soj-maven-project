### 
Open the project in Intellij IDEA

- run the clean and package tasks from the maven toolbar
- go to the target directory from the ```soj-mvn-app```, there you can find a zip file.
- unzip the file and go to the root until you find the libs and .jar file
- type cmd and then paste the command ```java -cp soj-mvn-app-1.0.0-SNAPSHOT.jar;libs/* org.endava.tmd.MyApp Charlie Chaplin```
- the result should looks like this:
``` Am construit persoana: org.endava.tmd.soj.maven.model.Person@2d98a335[firstName=Charlie,lastName=Chaplin] { "type": "success", "value": { "id": 466, "joke": "Charlie Chaplin doesn't do Burn Down charts, he does Smack Down charts.", "categories": ["nerdy"] } }
```
