# Release Ops-2 | `20` / `20` pts. | Status: In Progress
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
# Epics -- Estimated: 19 / Actual: 19 pts.
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
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Create a cloudfront distribution for the above S3 bucket</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/2">pulumi-aws-static-ui-services/#2</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Application List Refactor</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/4">pulumi-aws-static-ui-services/#4</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Figure out SSL for the front ends</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/5">pulumi-aws-static-ui-services/#5</a></td> </tr>
</table>
</p>


### `Epic` - Secrets Nuget Package, Look at Cache / Rotating Cache - `0`/`0` pts. - :x:open - [zenhub-product/#30](https://github.com/OnboardRS/zenhub-product/issues/30)


 > With our DB secrets rotating every 14 days, if we aren't refreshing secrets in the pods... every 2 weeks we are going to have an outage until we bounce pods.

#### Labels: Epic ops 
---
### `Epic` - Cluster Internal Ingress / Private Routing - `11`/`11` pts. - :x:open - [zenhub-product/#32](https://github.com/OnboardRS/zenhub-product/issues/32)


#### Labels: Epic ops 
---
Linked Issues: `2`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>Internal K8s Ingress</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/18">zenhub-ops/#18</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Route53 Private Hosted Zone</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/19">zenhub-ops/#19</a></td> </tr>
</table>
</p>


### `Epic` - Static Front End CI/CD GitHub Action - `0`/`0` pts. - :x:open - [zenhub-product/#31](https://github.com/OnboardRS/zenhub-product/issues/31)


#### Labels: Epic ops 
---
### `Epic` - Cognito - `0`/`0` pts. - :x:open - [zenhub-product/#34](https://github.com/OnboardRS/zenhub-product/issues/34)


 > We need to pulumi this out...
 >We need to design / plan our cognito strategy
 >We need to do massive discovery
 >
 >

#### Labels: Epic ops 
---
### `Epic` - onboardrs-todo-issues - `0`/`0` pts. - :x:open - [zenhub-ops/#24](https://github.com/OnboardRS/zenhub-ops/issues/24)


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

## Issues without Epics: || 1 pts.
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>Log retention for control plane logging</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-eks/issues/1">pulumi-aws-eks/#1</a></td> </tr>
</table>
