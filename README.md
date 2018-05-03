
# chart-es-curator
This repository contains 1 chart that is used to deploy es-curator to kubernetes.
- es-curator

install `es-curator` chart
```
helm install --name es-curator chartmuseum/es-curator
```

### Below are the configurable parameter for this
- cronSchedule
- esHost
- esPort
- snapshotName
- bucketName
- bucketBasePath
- awsRegion
- timeUnit
- olderThan
- loglevel
