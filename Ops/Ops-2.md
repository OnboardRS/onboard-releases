# Release Ops-2 | `44` / `44` pts. | Status: In Progress
_Release Date: 2022-05-26_


 > This release is the follow up infrastructure release to support the new AWS ecosystem.
 >
 >Key Milestones:
 >
 >- Internal cluster routing
 >- Private DNS resolution for internal only service
 >- VPN private DNS resolution
 >- Consistent CI/CD process for static hosted frontends
 >- Consistent infrastructure for static hosted frontends, builds S3 bucket, CloudFront Distro, SSL, and Route53 records
 >- Cognito, we now have internal user pools for internal applications
 >- Staging Environment Stood Up (w/ Marketing Materials Release)
 >- Prod Environment Stood Up (w/ Marketing Materials Release)
---
# Epics -- Estimated: 37 / Actual: 37 pts.
### `Epic` - Make pulumi-aws-static-ui-services dynamic for future projects - `8`/`8` pts. - :heavy_check_mark:closed - [zenhub-product/#29](https://github.com/OnboardRS/zenhub-product/issues/29)


 > Write now in sake of time it is built with a single domain. 
 >Would be much better long term to have a list of application names in the pulumi config.
 >Then iterate through each application name and create the s3 bucket / cloudfront / route53

#### Labels: Epic ops 
---
Linked Issues: `3`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Create a cloudfront distribution</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/2">pulumi-aws-static-ui-services/#2</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Application List Refactor</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/4">pulumi-aws-static-ui-services/#4</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Figure out SSL for the front ends</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/5">pulumi-aws-static-ui-services/#5</a></td> </tr>
</table>
</p>


### `Epic` - Cluster Internal Ingress / Private Routing - `11`/`11` pts. - :heavy_check_mark:closed - [zenhub-product/#32](https://github.com/OnboardRS/zenhub-product/issues/32)


#### Labels: Epic ops 
---
Linked Issues: `2`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>Internal K8s Ingress</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/18">zenhub-ops/#18</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Route53 Private Hosted Zone</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/19">zenhub-ops/#19</a></td> </tr>
</table>
</p>


### `Epic` - Static Front End CI/CD GitHub Action - `5`/`5` pts. - :heavy_check_mark:closed - [zenhub-product/#31](https://github.com/OnboardRS/zenhub-product/issues/31)


#### Labels: Epic ops 
---
Linked Issues: `2`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Build the thing</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-product/issues/42">zenhub-product/#42</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Invalidate the cloudfront cache</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-product/issues/43">zenhub-product/#43</a></td> </tr>
</table>
</p>


### `Epic` - Cognito - `5`/`5` pts. - :heavy_check_mark:closed - [zenhub-product/#34](https://github.com/OnboardRS/zenhub-product/issues/34)


 > We need to pulumi this out...
 >We need to design / plan our cognito strategy
 >We need to do massive discovery
 >
 >

#### Labels: Epic ops 
---
Linked Issues: `4`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>Cognito Role</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-cognito/issues/1">pulumi-aws-cognito/#1</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>App Client</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-cognito/issues/2">pulumi-aws-cognito/#2</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>SecretsManager Secret</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-cognito/issues/3">pulumi-aws-cognito/#3</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>UserPool</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-cognito/issues/4">pulumi-aws-cognito/#4</a></td> </tr>
</table>
</p>


### `Epic` - [Staging] Release Ticket - `0`/`0` pts. - :heavy_check_mark:closed - [zenhub-product/#41](https://github.com/OnboardRS/zenhub-product/issues/41)


 > - [x] Amazon Cognito policy PowerUser attached to basic pod role
 >- [x] pulumi-aws-iam
 >- [x] pulumi-aws-eks
 >- [x] pulumi-aws-k8s
 >- [x] pulumi-aws-s3
 >- [x] pulumi-aws-secrets
 >- [x] pulumi-aws-cognito
 >- [x] pulumi-aws-mysql
 >- [x] pulumi-aws-route53-onboard-io
 >- [x] create SSL cert in us-east-1 (thanks cloudfront)
 >- [x] pulumi-aws-static-ui-services
 >- [x] deploy app-marketing-materials
 >- [x]  deploy app-inflight
 >- [x] deploy marketing-materials service
 >- [x] deploy property-service-c
 >- [x] deploy marketing-management-api
 >
 >

#### Labels: marketing-materials release Epic ops 
---
### `Epic` - [Production] Release Ticket  - `0`/`0` pts. - :heavy_check_mark:closed - [zenhub-product/#40](https://github.com/OnboardRS/zenhub-product/issues/40)


 > - [x] Amazon Cognito policy PowerUser attached to basic pod role
 >- [x]  pulumi-aws-iam
 >- [x]  pulumi-aws-eks
 >- [x]  pulumi-aws-k8s
 >- [x]  pulumi-aws-s3
 >- [x]  pulumi-aws-secrets
 >- [x]  pulumi-aws-cognito
 >- [x]  pulumi-aws-dms-mysql
 >- [x]  pulumi-aws-route53-onboard-io
 >- [x]  pulumi-aws-static-ui-services
 >- [x]  migrate onboardrs.com DNS to route53
 >- [x]  deploy app-inflight
 >- [x] deploy app-marketing-materials
 >- [x] deploy marketing-materials service
 >- [x] deploy property-service-c
 >- [x] deploy marketing-management-api
 >

#### Labels: marketing-materials release Epic ops 
---
### `Epic` - onboardrs-todo-issues - `8`/`8` pts. - :x:open - [zenhub-ops/#24](https://github.com/OnboardRS/zenhub-ops/issues/24)


 > Take the existing `todo-issues.yml` and make `onboard-todo.yml`
 >
 >- [ ] don't close issues when you remove todo comment
 >- [ ] default create all issues in the github repo zenhub-dev
 >- [ ] allow for a default label in the action config
 >
 >example: rent-roll
 >So all rent-roll repos they process todo comments -> create an issue in zenhub-dev and apply the label rent-roll

#### Labels: Epic ops 
---
Linked Issues: `1`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>Build the thing</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/26">zenhub-ops/#26</a></td> </tr>
</table>
</p>



## Issues without Epics: || 7 pts.
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>Update readme on app usage</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-ecr/issues/1">pulumi-aws-ecr/#1</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>Log retention for control plane logging</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-eks/issues/1">pulumi-aws-eks/#1</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Research lifescycle policies and determine what we want</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-ecr/issues/2">pulumi-aws-ecr/#2</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>Define a lifecycle and repo policy</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-ecr/issues/3">pulumi-aws-ecr/#3</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>onboardrs.com DNS migration to Route53</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/25">zenhub-ops/#25</a></td> </tr>
</table>
