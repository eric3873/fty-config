#!/usr/bin/env groovy

@Library('etn-ipm2-jenkins') _

import params.CmakePipelineParams
CmakePipelineParams parameters = new CmakePipelineParams()
parameters.debugBuildRunCoverage = false

etn_ipm2_build_and_tests_pipeline_cmake(parameters)
