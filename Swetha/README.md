# java-word-count-beam
# A sample wordcount example pipeline using apache beam Java SDK


## Checking java version
java --version

## Checking maven version
maven --version

## Use the following command to generate a Maven project that contains Beam’s WordCount examples and builds against the most recent Beam release:
mvn archetype:generate `
 -D archetypeGroupId=org.apache.beam `
 -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
 -D archetypeVersion=2.36.0 `
 -D groupId=org.example `
 -D artifactId=word-count-beam `
 -D version="0.1" `
 -D package=org.apache.beam.examples `
 -D interactiveMode=false

## Sample text
Created sample.txt file, Used the text of Shakespeare’s Sonnets.

## To run Wordcount
mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
Inspecting results
$ ls counts*

## Execute PR Quick Start Command
mvn compile exec:java -D exec.mainClass=edu.nwmsu.section02group05.swetha.MinimalPageRankSwetha

## Link for Issues 

(https://github.com/RohitChandupatla/beam-java/issues)

## Link for Wiki

(https://github.com/RohitChandupatla/beam-java/wiki/Gahana-Swetha-Sanagala)

## Link for MinimalPagerankSwetha

(https://github.com/RohitChandupatla/beam-java/blob/main/Swetha/src/main/java/edu/nwmsu/section02group05/swetha/MinimalPageRankSwetha.java)

## Link for my Folder

(https://github.com/RohitChandupatla/beam-java/tree/main/Swetha)

## Link for Commits

(https://github.com/RohitChandupatla/beam-java/commits/main)

## Link for Main Project 

(https://github.com/RohitChandupatla/beam-java)




