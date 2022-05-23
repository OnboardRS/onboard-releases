# Release Ops-2 | `20` / `20` pts. | Status: In Progress
_Release Date: 2022-05-26_


 > This release is the follow up infrastructure release to support the new AWS ecosystem.
 >
 >Key Milestones:
 >
 >- Internal cluster routing
 >- Mutual TLS between services
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
Linked Issues: `0`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
</table>
</p>


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
Linked Issues: `0`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
</table>
</p>


### `Epic` - Pod Role Management - `0`/`0` pts. - :x:open - [zenhub-product/#33](https://github.com/OnboardRS/zenhub-product/issues/33)


 > Repo: `pulumi-aws-s3`
 >
 >We need to walk through this and figure out how to improve this.
 >Do we have a set of base pod policies that we reach out an attach custom polices to?
 >
 >Etc etc... Design convo / discovery

#### Labels: Epic ops 
---
Linked Issues: `0`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
</table>
</p>


### `Epic` - Cognito - `0`/`0` pts. - :x:open - [zenhub-product/#34](https://github.com/OnboardRS/zenhub-product/issues/34)


 > We need to pulumi this out...
 >We need to design / plan our cognito strategy
 >We need to do massive discovery
 >
 >

#### Labels: Epic ops 
---
Linked Issues: `0`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
</table>
</p>


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
Linked Issues: `0`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
</table>
</p>


### `Epic` - DNS Migration - `0`/`0` pts. - :x:open - [zenhub-ops/#6](https://github.com/OnboardRS/zenhub-ops/issues/6)


 > - [ ] onboardrs.com
 >- [ ] mediaamenity.com
 >- [ ] onboardassembly.com
 >- [ ] onboardtoday.com
 >- [ ] letsonboard.com
 >
 >

#### Labels: Epic ops 
---
Linked Issues: `15`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Dev Route53</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-com/pull/1">pulumi-aws-route53-onboardrs-com/#1</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Build pulumi.master.yaml</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/1">pulumi-aws-route53-onboardtoday/#1</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Dev Route53 w/ Action</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-com/pull/2">pulumi-aws-route53-onboardrs-com/#2</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Build Hosted Zone</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/2">pulumi-aws-route53-onboardtoday/#2</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Rebuild Dev Hosted Zone</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-com/pull/3">pulumi-aws-route53-onboardrs-com/#3</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Add Test record</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/3">pulumi-aws-route53-onboardtoday/#3</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>IT Route53</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-com/pull/4">pulumi-aws-route53-onboardrs-com/#4</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Production Only Records</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/4">pulumi-aws-route53-onboardtoday/#4</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Added config files for staging/prod</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-com/pull/5">pulumi-aws-route53-onboardrs-com/#5</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Build TXT Records for onboardtoday.com</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/5">pulumi-aws-route53-onboardtoday/#5</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Prod Route53</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-com/pull/6">pulumi-aws-route53-onboardrs-com/#6</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Build MX Records for onboardtoday.com</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/6">pulumi-aws-route53-onboardtoday/#6</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Web UI Records for LEGACY ADMIN</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/7">pulumi-aws-route53-onboardtoday/#7</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Application records</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/8">pulumi-aws-route53-onboardtoday/#8</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>ACM Cert and Domain Verification records</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardtoday/issues/9">pulumi-aws-route53-onboardtoday/#9</a></td> </tr>
</table>
</p>



## Issues without Epics: || 1 pts.
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>Log retention for control plane logging</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-eks/issues/1">pulumi-aws-eks/#1</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Private Hosted Zone to Staging</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-io/pull/1">pulumi-aws-route53-onboardrs-io/#1</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Private Hosted Zone to Prod</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-route53-onboardrs-io/pull/2">pulumi-aws-route53-onboardrs-io/#2</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Deploy Staging MYSQL</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/pull/9">pulumi-aws-mysql/#9</a></td> </tr>
</table>
