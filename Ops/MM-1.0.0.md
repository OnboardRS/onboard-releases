# Release MM-1.0.0 || TotalPoints: 42 || Status: In Progress
_Release Date: 2022-05-12_
 > This is the operational infrastructure to build CI/CD to support the Marketing Materials Project
---
# Epics || 42 pts.
### `Epic` - Automate RDS Snapshot Sharing Between Accounts - +`5 pts.` - :heavy_check_mark:closed - [zenhub-product/#25](https://github.com/OnboardRS/zenhub-product/issues/25)
 > Applies to the `AWS-Prod` account for RDS instances `onboardrs-prod-mysql` and `onboardrs-prod-sqlserver`

- [x] Convert System Snapshot to Manual Snapshot
- [x] Share snapshot with other accounts
- [x] Automate this stuff, so we don't have to think about it again


#### Labels: Epic ops 
---
Linked Issues: `1` with a total of `5` pts.
<p>
<table>
<tr><th>Pts</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+5</td><td>Issue</td><td>Setup Prod MYSQL snapshot sharing to Dev & Staging</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/1">pulumi-aws-mysql/#1</a></td> </tr>
</table>
</p>


### `Epic` - pulumi-aws-s3 - +`0 pts.` - :x:open - [zenhub-product/#26](https://github.com/OnboardRS/zenhub-product/issues/26)
 > We need a top level pulumi project for S3 buckets that are needed by services, but ARE NOT hosting UI.
These are purely data buckets in a central location to manage them.

Ideally we would use this naming convention.


`{lane}-bucket-name` drop `{lane}` off production buckets.

Example:
Dev: `dev-rent-roll`
Stage: `staging-rent-roll`
Prod: `rent-roll`

When in doubt use `onboardrs` in bucket names for uniqueness

#### Labels: Epic ops 
---
Linked Issues: `0` with a total of `0` pts.
<p>
<table>
<tr><th>Pts</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
</table>
</p>


### `Epic` - pulumi-aws-mysql - +`19 pts.` - :heavy_check_mark:closed - [zenhub-product/#22](https://github.com/OnboardRS/zenhub-product/issues/22)
 > MYSQL RDS in lower lanes that create off a shared snapshot from AWS-Prod

#### Labels: Epic ops 
---
Linked Issues: `8` with a total of `19` pts.
<p>
<table>
<tr><th>Pts</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+5</td><td>Issue</td><td>Setup Prod MYSQL snapshot sharing to Dev & Staging</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/1">pulumi-aws-mysql/#1</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>Pulumi ENV and Configs for Dev/Stage</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/2">pulumi-aws-mysql/#2</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>RDS Subnet Group</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/3">pulumi-aws-mysql/#3</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>RDS Security Group</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/4">pulumi-aws-mysql/#4</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>RDS Parameter Group</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/5">pulumi-aws-mysql/#5</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>RDS MYSQL</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/6">pulumi-aws-mysql/#6</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>AWS Secrets Manager</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/7">pulumi-aws-mysql/#7</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>AWS Secret Rotation</td><td></td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-mysql/issues/8">pulumi-aws-mysql/#8</a></td> </tr>
</table>
</p>


### `Epic` - K8s CI/CD - +`14 pts.` - :x:open - [zenhub-ops/#17](https://github.com/OnboardRS/zenhub-ops/issues/17)
 > This is the generic CI/CD work that needs to take place, before we can onboard the marketing materials app into the eco system.

#### Labels: Epic ops 
---
Linked Issues: `5` with a total of `14` pts.
<p>
<table>
<tr><th>Pts</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>Issue</td><td>Remove Keptn</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/10">zenhub-ops/#10</a></td> </tr>
<tr><td>+3</td><td>Issue</td><td>GitHub Action CI and Dev CD</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/11">zenhub-ops/#11</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>Discovery - Helm chart persistence</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/12">zenhub-ops/#12</a></td> </tr>
<tr><td>+5</td><td>Issue</td><td>GitHub Action Helm</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/13">zenhub-ops/#13</a></td> </tr>
<tr><td>+3</td><td>Issue</td><td>GitHub Action CD Stage/Prod</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/14">zenhub-ops/#14</a></td> </tr>
</table>
</p>


### `Epic` - AWS UI Service Infrastructure - +`4 pts.` - :heavy_check_mark:closed - [zenhub-ops/#8](https://github.com/OnboardRS/zenhub-ops/issues/8)
 > This is for the UI architecture that results in:

- S3 Hosted static frontend
- CloudFront Distro
- Route53

This will be it's own pulumi project with accompanying todos

#### Labels: Epic ops 
---
Linked Issues: `2` with a total of `4` pts.
<p>
<table>
<tr><th>Pts</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>Issue</td><td>Create S3 bucket for marketing-materials.{env}-onboardrs.com</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/1">pulumi-aws-static-ui-services/#1</a></td> </tr>
<tr><td>+2</td><td>Issue</td><td>Create Route53 record for marketing-materials.{env}-onboardrs.com</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/pulumi-aws-static-ui-services/issues/3">pulumi-aws-static-ui-services/#3</a></td> </tr>
</table>
</p>



## Issues || 0 pts.
<table>
<tr><th>Pts</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
</table>
