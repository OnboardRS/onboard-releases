# Release Ops-3 | `26` : `26` pts. | Status: In Progress
_Release Date: 2022-06-10_


 > 
---
# Epics -- Estimated: 24  Actual: 24 pts.
### `Epic` - Legacy Admin -- Migrate Digital Ocean to AWS - `0`:`0` pts. - :x:open - [zenhub-product/#23](https://github.com/OnboardRS/zenhub-product/issues/23)


#### Labels: Epic ops 
---
### `Epic` - Secrets Nuget Package, Look at Cache / Rotating Cache - `0`:`0` pts. - :x:open - [zenhub-product/#30](https://github.com/OnboardRS/zenhub-product/issues/30)


 > With our DB secrets rotating every 14 days, if we aren't refreshing secrets in the pods... every 2 weeks we are going to have an outage until we bounce pods.

#### Labels: Epic ops 
---
### `Epic` - Pod Role Management - `0`:`0` pts. - :x:open - [zenhub-product/#33](https://github.com/OnboardRS/zenhub-product/issues/33)


 > Repo: `pulumi-aws-s3`
 >
 >We need to walk through this and figure out how to improve this.
 >Do we have a set of base pod policies that we reach out an attach custom polices to?
 >
 >Etc etc... Design convo / discovery

#### Labels: Epic ops 
---
### `Epic` - Helm Chart Environment Variables -- Make Better - `0`:`0` pts. - :x:open - [zenhub-product/#35](https://github.com/OnboardRS/zenhub-product/issues/35)


#### Labels: Epic ops 
---
### `Epic` - Cronjob HelmCharts - `0`:`0` pts. - :x:open - [zenhub-product/#48](https://github.com/OnboardRS/zenhub-product/issues/48)


 > We need a helmchart for cronjob projects in our k8s cluster

#### Labels: Epic ops 
---
### `Epic` - pulumi-aws-dms-postgres - `24`:`24` pts. - :x:open - [zenhub-product/#51](https://github.com/OnboardRS/zenhub-product/issues/51)


 > Do the DMS thing, to the GCP Postgres
 >This is to migrate the data from GCP into AWS for testing, so we can test / safely tear down GCP

#### Labels: Epic ops 
---
Linked Issues: `12`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>pulumi-dms-postgres: Config</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/39">zenhub-dev/#39</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: DMS Role</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/40">zenhub-dev/#40</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: Subnet Group</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/41">zenhub-dev/#41</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: Replication Instance</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/42">zenhub-dev/#42</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: Ingress List / Security Group</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/43">zenhub-dev/#43</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: RDS Subnet Group</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/44">zenhub-dev/#44</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: RDS Parameter Group</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/45">zenhub-dev/#45</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: RDS Instance</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/46">zenhub-dev/#46</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: AWS Secrets and Secret Rotation</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/47">zenhub-dev/#47</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>pulumi-dms-postgres: AWS Secrets Lambda Payload for Postgres</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/48">zenhub-dev/#48</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: DMS Endpoints</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/49">zenhub-dev/#49</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>pulumi-dms-postgres: DMS Replication Task</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/50">zenhub-dev/#50</a></td> </tr>
</table>
</p>


### `Epic` - Legacy Admin PubSub - `0`:`0` pts. - :x:open - [zenhub-product/#52](https://github.com/OnboardRS/zenhub-product/issues/52)


 > - [ ] Create dev pubsub
 >- [ ] Create staging pubsub

#### Labels: Epic ops 
---
### `Epic` - pulumi-aws-postgres - `0`:`0` pts. - :x:open - [zenhub-ops/#29](https://github.com/OnboardRS/zenhub-ops/issues/29)


 > Build the same setup as the mysql environment.
 >Where dev and staging get built of shared snapshots from production

#### Labels: Epic ops 
---
Linked Issues: `7`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-postgres: Config and Data Queries</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/51">zenhub-dev/#51</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-postgres: RDS SubnetGroup</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/52">zenhub-dev/#52</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-postgres: Ingress List and SecurityGroup</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/53">zenhub-dev/#53</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-postgres: RDS ParameterGroup</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/54">zenhub-dev/#54</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-postgres: RDS Instance</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/55">zenhub-dev/#55</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-postgres: AWS Secrets Lambda Payload for Postgres</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/56">zenhub-dev/#56</a></td> </tr>
<tr><td>+0</td><td>+0</td><td>Issue</td><td>pulumi-aws-postgres: AWS Secrets and Secret Rotation</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/57">zenhub-dev/#57</a></td> </tr>
</table>
</p>



## Issues without Epics: || 2 pts.
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>DMS -- IAM Role, needs CloudWatch access</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-ops/issues/20">zenhub-ops/#20</a></td> </tr>
</table>
