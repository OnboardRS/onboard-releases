# Release Ops-8 | `39` : `43` pts. | Status: Released
_Release Date: 2022-08-19_


 > - [dev] - K8s cluster revamp/resize
 >- [zd] - Zendesk Support for Opt-Out flows
 >- [dev,staging,prod] - Image App, hosting for pinpoint images
 >- [dev] - PHP Admin in AWS
---
# Epics -- Estimated: 36  Actual: 40 pts.
### `Epic` - [dev] - Configure Legacy Admin Ecosystem - `8`:`8` pts. - :heavy_check_mark:closed - [zenhub-dev/#239](https://github.com/OnboardRS/zenhub-dev/issues/239)


#### Labels: Epic ops 
---
Linked Issues: `2`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+5</td><td>+5</td><td>Issue</td><td>Legacy Admin Forge & Envoyer Setup</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/233">zenhub-dev/#233</a></td> </tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>[dev] - Test Forge and Envoyer reachability</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/240">zenhub-dev/#240</a></td> </tr>
</table>
</p>


### `Epic` - Kubernetes Cluster Refactor - `22`:`26` pts. - :x:open - [zenhub-dev/#322](https://github.com/OnboardRS/zenhub-dev/issues/322)


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
Linked Issues: `8`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+2</td><td>Issue</td><td>SPIKE - Decide on new cluster node size</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/323">zenhub-dev/#323</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Dev - Cluster resize</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/324">zenhub-dev/#324</a></td> </tr>
<tr><td>+8</td><td>+13</td><td>Issue</td><td>POC - Refactor cluster</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/327">zenhub-dev/#327</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Dev - Deploy cluster refactor</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/328">zenhub-dev/#328</a></td> </tr>
<tr><td>+3</td><td>+2</td><td>Issue</td><td>Prepare deployed applications for new cluster deployment</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/331">zenhub-dev/#331</a></td> </tr>
<tr><td>+2</td><td>+1</td><td>Issue</td><td>Dev - Deploy apps to new cluster</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/332">zenhub-dev/#332</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Dev - New cluster cutover</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/335">zenhub-dev/#335</a></td> </tr>
<tr><td>+2</td><td>+2</td><td>Issue</td><td>Dev - Old cluster cleanup</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/338">zenhub-dev/#338</a></td> </tr>
</table>
</p>


### `Epic` - Image Hosting for Pinpoint Images - `3`:`3` pts. - :heavy_check_mark:closed - [zenhub-dev/#252](https://github.com/OnboardRS/zenhub-dev/issues/252)


 > Create img as a frontend static app to replace image hosting out of php app

#### Labels: Epic ops 
---
Linked Issues: `3`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[dev] -- Create img app</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/255">zenhub-dev/#255</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[staging] -- Create img app</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/256">zenhub-dev/#256</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[prod] -- Create img app</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/257">zenhub-dev/#257</a></td> </tr>
</table>
</p>


### `Epic` - Zendesk Custom Fields for Opt-Out - `3`:`3` pts. - :heavy_check_mark:closed - [zenhub-dev/#263](https://github.com/OnboardRS/zenhub-dev/issues/263)


 > We need to add a few custom fields to Zendesk to make the new opt-out flow on landing pages better
 >
 >Ticket Type: [drop-down]
 >- Resident Support
 >- Property Support
 >- Opt-Out
 >
 >Opt-Out Reason: [drop-down]
 >- I’m currently paying less for similar services.
 >- I’m moving out soon.
 >- I don’t want to switch providers.
 >- I already utilize services from this provider.
 >- Other.
 >
 >In addition to these fields, we need to update the existing automations that currently categorize emails into groups. To have it also set the Ticket Type.
 >
 >We need to do some additional training with the RSAs for when a user by passes the opt-out form, and just sends in an email:
 >
 >People who just email in to opt-out will create a new Resident Support ticket.
 >We need to show the RSAs when you get an opt-out ticket via Resident Support Email:
 >
 >-  Update the ticket type to opt-out 
 >-  Talk to the resident and find out why and update it in the drop down
 >
 >
 >Reference Docs:
 >![image.png](https://images.zenhubusercontent.com/623b9450b52d5c969dd04278/a790e8f0-1631-441d-a79a-3f5fc931f650)
 >https://support.zendesk.com/hc/en-us/articles/4408824384538-Reporting-with-custom-fields
 >
 >

#### Labels: Epic ops 
---
Linked Issues: `3`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[zd] Create Custom Fields</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/264">zenhub-dev/#264</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[zd] Update Automations</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/265">zenhub-dev/#265</a></td> </tr>
<tr><td>+1</td><td>+1</td><td>Issue</td><td>[zd] Update Agent Views</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/266">zenhub-dev/#266</a></td> </tr>
</table>
</p>



## Issues without Epics: || 3 pts.
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+3</td><td>+3</td><td>Issue</td><td>Build deploy process for pinpoint templates</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/351">zenhub-dev/#351</a></td> </tr>
</table>
