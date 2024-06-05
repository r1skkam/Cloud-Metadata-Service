# Cloud Metadata Service

Cloud Metadata Service (AWS, Azure and GCP)

[Retrieve instance metadata - Amazon Elastic Compute Cloud](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instancedata-data-retrieval.html)

http://169.254.169.254/latest/meta-data/

http://[fd00:ec2::254]/latest/meta-data/

[Azure Instance Metadata Service for virtual machines - Azure Virtual Machines | Microsoft Learn](https://learn.microsoft.com/en-us/azure/virtual-machines/instance-metadata-service?tabs=linux)

```
curl -s -H Metadata:true --noproxy "*" "http://169.254.169.254/metadata/instance?api-version=2021-02-01" | jq
```

[View and query VM metadata &nbsp;|&nbsp; Compute Engine Documentation &nbsp;|&nbsp; Google Cloud](https://cloud.google.com/compute/docs/metadata/querying-metadata)

http://metadata.google.internal/computeMetadata/v1

http://169.254.169.254/computeMetadata/v1

http://metadata.goog/computeMetadata/v1
