# Release Ops-7 | `71` : `71` pts. | Status: Released
_Release Date: 2022-08-05_


 > This release focuses on:
 >
 >- Zendesk Rollout (Email Only)
 >- Fixing our internal certs for onboardrs.io
 >- Deploying the new queue architecture into dev
 >  - This is for pinpoint and new rent-roll
 >  - RealPage is working on new queue system
 >  - Pinpoint provisioner and refresher are on the new queue system
 >- Starting the migration of Legacy Admin to AWS. 
 >  - The servers and ecosystem are stood up, next sprint will work on configuring the environment
 >
---
# Epics -- Estimated: 49  Actual: 49 pts.
### `Epic` - Pod Role Management - `0`:`0` pts. - :heavy_check_mark:closed - [zenhub-product/#33](https://github.com/OnboardRS/zenhub-product/issues/33)


 > Repo: `pulumi-aws-s3`
 >
 >We need to walk through this and figure out how to improve this.
 >Do we have a set of base pod policies that we reach out an attach custom polices to?
 >
 >Etc etc... Design convo / discovery

#### Labels: Epic ops 
---
Linked Issues: `1`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>Move the role creation from here to the centralized pod role repo</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/119">zenhub-dev/#119</a></td> </tr>
</table>
</p>


### `Epic` - Legacy Admin PubSub - `0`:`0` pts. - :heavy_check_mark:closed - [zenhub-product/#52](https://github.com/OnboardRS/zenhub-product/issues/52)


 > - [x] Create dev pubsub
 >- [ ] Create staging pubsub

#### Labels: Epic ops 
---
### `Epic` - Legacy Admin -- Migrate Digital Ocean to AWS - `13`:`13` pts. - :heavy_check_mark:closed - [zenhub-product/#23](https://github.com/OnboardRS/zenhub-product/issues/23)


 > ![onboardrs-legacy-admin.png](https://images.zenhubusercontent.com/623b9450b52d5c969dd04278/c6f97e3c-3350-40ad-8389-08492578af41)

#### Labels: Epic ops 
---
Linked Issues: `6`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Legacy Admin EC2s</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/228">zenhub-dev/#228</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Legacy Admin Elastic IPs</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/229">zenhub-dev/#229</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Legacy Admin ELB</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/230">zenhub-dev/#230</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Legacy Admin Route53</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/231">zenhub-dev/#231</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Legacy Admin SG</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/232">zenhub-dev/#232</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Setup dev- and staging- domains / zones / certs for onboardtoday.com and letsonboard.com</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/235">zenhub-dev/#235</a></td> </tr>
</table>
</p>


### `Epic` - ZenDesk POC - `16`:`16` pts. - :heavy_check_mark:closed - [zenhub-ops/#5](https://github.com/OnboardRS/zenhub-ops/issues/5)


 > Reach out to ZenDesk to get a trial going.
 >Need to see if we can qualify for the 6 months free startup account.
 >
 >I'll add additional tasks to this later.

#### Labels: Epic ops 
---
Linked Issues: `6`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[zd] - Create Instance</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/222">zenhub-dev/#222</a></td> </tr>
<tr><td>+5</td><td>+5</td><td>Issue</td><td>[zd] - SSO with Gsuite</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/223">zenhub-dev/#223</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>[zd] - Import Users</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/224">zenhub-dev/#224</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>[zd] - Create Groups</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/225">zenhub-dev/#225</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>[zd] - Setup Support Emails</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/226">zenhub-dev/#226</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>[zd] - Setup Basic Views</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/227">zenhub-dev/#227</a></td> </tr>
</table>
</p>


### `Epic` - Fix onboardrs.io self signed certs - `20`:`20` pts. - :heavy_check_mark:closed - [zenhub-dev/#189](https://github.com/OnboardRS/zenhub-dev/issues/189)


 > Kyle brought it to my attention that we were having issues with the private hosted zones and the self signed certs.
 >This was leading to applications ignoring SSL cert errors in order to run. Which opens us up to potential security vulnerabilities.
 >
 >After some research and poking around I came up with a fix to resolve this issue.
 >
 >1 - Create a public zone for our onboardrs.io domains that overlaps with the private
 >2 - Create an amazon issued cert for onboardrs.io
 >3 - Create the cert validation DNS records in the newly created public hosted zone
 >4 - Destroy self signed certs and the ACM cert manager that we are hosting.
 >
 >Result: We can maintain internal DNS / use an amazon issued cert / and save $400/mo by avoiding the self signed certs all together.

#### Labels: Epic ops 
---
Linked Issues: `19`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] Create public hosted zone</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/190">zenhub-dev/#190</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] Create new amazon issued cert</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/191">zenhub-dev/#191</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] Create cert validation records in route53</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/192">zenhub-dev/#192</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] Add public zone name servers to domain</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/193">zenhub-dev/#193</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] Replace load balancer cert with new cert</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/194">zenhub-dev/#194</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] Delete self signed cert from environment</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/195">zenhub-dev/#195</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[staging] Delete self signed cert from environment</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/199">zenhub-dev/#199</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[staging] Replace load balancer cert with new cert</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/200">zenhub-dev/#200</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[staging] Add public zone name servers to domain</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/201">zenhub-dev/#201</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[staging] Create cert validation records in route53</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/202">zenhub-dev/#202</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[staging] Create new amazon issued cert</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/203">zenhub-dev/#203</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[staging] Create public hosted zone</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/204">zenhub-dev/#204</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[prod] Delete self signed cert from environment</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/205">zenhub-dev/#205</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[prod] Replace load balancer cert with new cert</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/206">zenhub-dev/#206</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[prod] Add public zone name servers to domain</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/207">zenhub-dev/#207</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[prod] Create cert validation records in route53</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/208">zenhub-dev/#208</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[prod] Create new amazon issued cert</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/209">zenhub-dev/#209</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[prod] Create public hosted zone</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/210">zenhub-dev/#210</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>[prod] Remove ACM Cert Authority from AWS-Prod</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/211">zenhub-dev/#211</a></td> </tr>
</table>
</p>



## Issues without Epics: || 22 pts.
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>DMS -- IAM Role, needs CloudWatch access</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/20">zenhub-ops/#20</a></td> </tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>Queue System Deployment Development and Testing - RentRoll</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/241">zenhub-dev/#241</a></td> </tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>Queue System Deployment Development and Testing - PinPoint</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/242">zenhub-dev/#242</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>New ACM Certs to K8s Cluster</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/243">zenhub-dev/#243</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Deploy rent-roll-api</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/244">zenhub-dev/#244</a></td> </tr>
</table>
