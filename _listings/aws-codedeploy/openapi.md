---
swagger: "2.0"
x-collection-name: AWS CodeDeploy
x-complete: 1
info:
  title: AWS CodeDeploy API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeregisterOnPremisesInstance:
    get:
      summary: Deregister On Premises Instance
      description: Deregisters an on-premises instance.
      operationId: deregisterOnPremisesInstance
      x-api-path-slug: actionderegisteronpremisesinstance-get
      parameters:
      - in: query
        name: instanceName
        description: The name of the on-premises instance to deregister
        type: string
      responses:
        200:
          description: OK
      tags:
      - On Premises Instances
---