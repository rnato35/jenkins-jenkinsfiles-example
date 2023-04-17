# Jenkins Pipeline Repository README

This repository contains the necessary files to execute a Jenkins pipeline correctly. The `Jenkinsfile` in this repository will be calling a `pipeline-library` shared library, which is set up in an external repository available [here](https://github.com/rnato35/jenkins-shared-lib-example).



The `Jenkinsfile` in this repository defines some required variables that will be used in the pipeline. These variables include:

## Docker variables:
  - `dockerfilePath`
  - `dockerImageName`
  - `dockerImageTag`
  - `dockerRegistry`

## EKS variables:
  - `eksClusterName`
  - `eksManifestFile`

More information regarding the pipeline functionality can be found in the shared library [repository](https://github.com/rnato35/jenkins-shared-lib-example) mentioned above.

## Setup

Before executing the pipeline, ensure that the `pipeline-library` shared library is properly set up in your Jenkins instance.

## Usage

To execute the pipeline, simply create a new Jenkins job and point it to this repository. Be sure to provide the path to the correct `Jenkinsfile`.

Please note that the required variables mentioned above must be properly defined in the Jenkins instance where the pipeline will be executed. If any of the variables are not properly defined, the pipeline will fail.