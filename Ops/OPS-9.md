# Release Ops-9 | `28` : `28` pts. | Status: In Progress
_Release Date: 2022-09-02_


 > 
---
# Epics -- Estimated: 28  Actual: 28 pts.
### `Epic` - Kubernetes Cluster Refactor - `21`:`21` pts. - :x:open - [zenhub-dev/#322](https://github.com/OnboardRS/zenhub-dev/issues/322)


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
Linked Issues: `10`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Staging - Cluster resize</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/325">zenhub-dev/#325</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Prod - Cluster resize</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/326">zenhub-dev/#326</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Staging - Deploy cluster refactor</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/329">zenhub-dev/#329</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Prod - Deploy cluster refactor</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/330">zenhub-dev/#330</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Staging - Deploy apps to new cluster</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/333">zenhub-dev/#333</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Prod - Deploy apps to new cluster</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/334">zenhub-dev/#334</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Staging - New cluster cutover</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/336">zenhub-dev/#336</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Prod - New cluster cutover</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/337">zenhub-dev/#337</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Staging - Old cluster cleanup</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/339">zenhub-dev/#339</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Prod - Old cluster cleanup</td><td>ops </td><td>:x:open</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/340">zenhub-dev/#340</a></td> </tr>
</table>
</p>


### `Epic` - Legacy Admin -> AWS, Improve storage and durability - `7`:`7` pts. - :x:open - [zenhub-dev/#362](https://github.com/OnboardRS/zenhub-dev/issues/362)


 > The way forge and envoyer work, the hosts for php admin have to be treated like pets.
 >
 >I would prefer to find a way to treat them like cattle, so we can bolt gun them in the head as needed.
 >In the current setup anytime we create a new host, we would have to manually intervene to register said host with forge and envoyer.
 >
 >The desired outcome from this EPIC is to use EBS storage in combination with Elastic IPs (already built).
 >So that when we have a new host come online, we can associate the EBS and EIP and not have to touch Forge/Envoyer configs.
 >
 >

#### Labels: Epic ops 
---
Linked Issues: `4`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>[dev] - Create EBS Volumes in pulumi-aws-legacy-admin-storage</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/363">zenhub-dev/#363</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>[dev] - Add EBS Lookup to pulumi-aws-legacy-admin</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/364">zenhub-dev/#364</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] - Create EIP in pulumi-aws-legacy-admin-storage</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/365">zenhub-dev/#365</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>[dev] - Add EIP lookup to pulumi-aws-legacy-admin</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/366">zenhub-dev/#366</a></td> </tr>
</table>
</p>


### `Epic` - Pinpoint Analytics - `0`:`0` pts. - :x:open - [zenhub-dev/#367](https://github.com/OnboardRS/zenhub-dev/issues/367)


 > This epic represents the AWS infrastructure around capturing AWS Pinpoint Events via a Kinesis stream.
 >This event feed will also represent an S3 partition to persist these events and later mount Athena on top to query for basic analytics.

#### Labels: Epic ops 
---

