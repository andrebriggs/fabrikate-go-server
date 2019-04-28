# go server 

[![Build Status](https://dev.azure.com/abrig/bedrock_gitops/_apis/build/status/andrebriggs.fabrikate-go-server?branchName=master)](https://dev.azure.com/abrig/bedrock_gitops/_build/latest?definitionId=6&branchName=master)

Go Server is a [Fabrikate](https://github.com/Microsoft/fabrikate) microservice definition.

If you are using Fabrikate and want to update the container image info:
`fab set --subcomponent go-server image.tag=IMAGE_TAG image.repository=IMAGE_REPO/IMAGE_NAME`

To perform an update for a particular environment (e.g. dev, qa, staging, prod, etc)
`fab set --environment ENV_NAME --subcomponent go-server image.tag=IMAGE_TAG image.repository=IMAGE_REPO`