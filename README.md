# Project Guidlines & Accomplishments

> pom.xml : edit and update new step-up versions for every module/submodule (maven artifect) within a repository which currently utilizes old deprecated dependency's version. It pushes a corresponding gerrit Review for all repositories provided as input.
 


- Features
  * confirms for special use-cases / quick alerts based customization for build-master
  * gerrit commit auto-templating
  * prompts for artifacts new_version input through cli
 


- Method xTree
  1. building dependency graph via reading recursively through directories
  2. Consider special condidtions for use-cases
  3. update the full dependency tree and then recursively update all pom.xml via implementing all of given features.
  4. commit message build

- Method Regex
  1. compile regex over specified version tags and extract information with pattern matching.
  2. Consider special condidtions for use-cases 
  3. use precompiled regex to put new_version of artifact and upgrade all mentioned artifacts throughout pom.xml.
  4. recursively update all pom.xml
  4. commit message build





