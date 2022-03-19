#!groovy
@Library('my-shared-library@master') _

Map configMap = [
	application:"lib",
]

echo "invoke pipelineApi..."
pipelineApi.execute(configMap)
echo "FINISHED"
