# Release Ops-10 | `43` : `43` pts. | Status: Released
_Release Date: 2022-09-16_


 > **Pinpoint:**
 >
 >- Pinpoint Analytics To Dev
 >- Pinpoint Lambda
 >- New Lambda CI/CD flow
 >
 >**K8s:**
 >
 >- Old Prod EKS cluster teardown
 >- Deploy Refactored Marketing Materials services 
 >
 >**Admin:**
 >
 >- Legacy Admin to Staging
 >
---
# Epics -- Estimated: 35  Actual: 35 pts.
### `Epic` - Kubernetes Cluster Refactor - `2`:`2` pts. - :heavy_check_mark:closed - [zenhub-dev/#322](https://github.com/OnboardRS/zenhub-dev/issues/322)


 > The K8s cluster in its current state was an unpolished PoC sent to prod as a hosting environment for new 2.0 services was needed immediately.
 >
 >After using it in this state for the past couple of months certain iterable improvements were noted and backlogged. This epic is for the representation of effort for the first of these improvements but more importantly for decoupling the monolithic cluster management into multiple chunks easier to affect by logical groupings, facilitating easier improvements in the future.
 >
 >Work to be done:
 >Resize the cluster onto new node types
 >Stand up a new second cluster
 >Deploy parallel cluster infrastructure
 >Prep and deploy applications to new cluster
 >Cut over with minimal to no downtime
 >Promote the cut over per environment 

#### Labels: Epic ops 
---
Linked Issues: `1`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Prod - Old cluster cleanup</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/340">zenhub-dev/#340</a></td> </tr>
</table>
</p>


### `Epic` - Pinpoint Analytics - `15`:`15` pts. - :heavy_check_mark:closed - [zenhub-dev/#367](https://github.com/OnboardRS/zenhub-dev/issues/367)


 > This epic represents the AWS infrastructure around capturing AWS Pinpoint Events via a Kinesis stream.
 >This event feed will also represent an S3 partition to persist these events and later mount Athena on top to query for basic analytics.
 >
 >![onboardrs-pinpoint-analytics.png](https://images.zenhubusercontent.com/623b9450b52d5c969dd04278/1af4e47f-a72b-46af-b3ac-bac768db30d2)

#### Labels: Epic ops 
---
Linked Issues: `4`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Build Lambda IAM policies</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/378">zenhub-dev/#378</a></td> </tr>
<tr><td>+13</td><td>+13</td><td>Issue</td><td>Build pinpoint-kinesis-lambda</td><td>ops resident-spaminator </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/379">zenhub-dev/#379</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-pinpoint-analytics: Add VPC Permissions to Lambda Role</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/437">zenhub-dev/#437</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-pinpoint-analytics: Add Security Group for Lambda</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/438">zenhub-dev/#438</a></td> </tr>
</table>
</p>


### `Epic` - Build Lambda CI/CD - `18`:`18` pts. - :heavy_check_mark:closed - [zenhub-dev/#380](https://github.com/OnboardRS/zenhub-dev/issues/380)


#### Labels: Epic ops 
---
Linked Issues: `3`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+5</td><td>+5</td><td>Issue</td><td>Lambda CI/CD Github Actions</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/404">zenhub-dev/#404</a></td> </tr>
<tr><td>+5</td><td>+5</td><td>Issue</td><td>Lambda CI/CD Dockerfile</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/405">zenhub-dev/#405</a></td> </tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>Lambda CI/CD Serverless</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/406">zenhub-dev/#406</a></td> </tr>
</table>
</p>



## Issues without Epics: || 8 pts.
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Update kubernetes / cicd flows for MM Proxy</td><td>marketing-materials ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/419">zenhub-dev/#419</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Update kubernetees / cicd flow for MM Service</td><td>marketing-materials ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/421">zenhub-dev/#421</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>[staging] - Standup Legacy Admin in staging</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/431">zenhub-dev/#431</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Sprint 10 Release</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/453">zenhub-dev/#453</a></td> </tr>
</table>
