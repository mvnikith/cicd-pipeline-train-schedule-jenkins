# cicd-pipeline-train-schedule-jenkins

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.

## Running the app

You need a Java JDK 7 or later to run the build. You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at [http://localhost:3000](http://localhost:3000)

Adding any changes in the Github will trigger the build, for example adding line no. 17 will trigger a new build.

Need to create a new trigger whenever changes are made, but by adding the line 17, the trigger didn't happen, need to check if the trigger happens by saving the line 19.
