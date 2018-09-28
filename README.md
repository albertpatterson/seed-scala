# Seed-Scala
A simple seed for a Scala project


## Usage
1) Clone this repo
2) Develop
2) (optional) update the remote origin to your own project: <br>```$> git remote set-url origin {your origin}```

## Notes
* Intellij can be used to run the project directly via the run menu/button/context menu
* Intellij can be used to run the tests directly via the run menu/button/context menu
    * Run all tests using the context menu of the ./src/test/java folder in the project window
    * tests can be triggered automatically upon source changes by performing the following
        * Build project automatically: Preferences > Build, Execution, Deployment > Compiler > Build project automatically
        * Run tests
        * Enable automatic rerun of tests via the toggle button in the run tool
* By default Scala sources are not packaged with the jar, use sbt assembly to create a fat jar for convenience:
<br>```$>sbt assembly```
* SBT can also be used to run test whenever src changes:
<br>in a sbt shell run ```> ~test```