This is the source code for the blog post on http://www.rainerhahnekamp.com/ignoring-lombok-code-in-jacoco/

It shows how to ignore code generated by Lombok in Jacoco >= 0.8.0.

Run the test and create the coverage report:
   * For maven execute `./mvnw test`. The jacoco report can be found in `./target/site/jacooco/index.html`.
   * For gradle run `./gradlew test jacocoTestReport`. The jacoco report can be cound in `./build/reports/jacoco/test/html/index.html`.
