#Equation-solver

##Goal
This repository aims at providing equation-solver (https://code.google.com/p/equation-solver/) as a library available via jcenter, easily usable with dependencies management tools.

##Usage
###To use this library:

add compile 'com.ahenry:equation-solver:0.0.4' in your build.gradle

###or

clone this repository and run:

gradlew clean build bintrayUpload -PbintrayUser=BINTRAY_USERNAME -PbintrayKey=BINTRAY_KEY -PdryRun=false to upload this library to your bintray repository
