# Release Ops-5 | `16` : `16` pts. | Status: Released
_Release Date: 2022-07-08_


 > CI/CD Rework
---
# Epics -- Estimated: 16  Actual: 16 pts.
### `Epic` - CI/CD Rework - `16`:`16` pts. - :heavy_check_mark:closed - [zenhub-product/#57](https://github.com/OnboardRS/zenhub-product/issues/57)


 > We needed to rework how we put CI/CD together.
 >Pulumi & FrontEnds were deploying with branch merges
 >Services were deploying with copy & paste on demand CD runs that were prone to human error if you got the wrong git sha.
 >
 >Design considerations:
 >
 >1. Allow devs to use GitFlow
 >2. Have CD deploy via merge or pull request
 >3. Have CI branches: dev/release/hotfix
 >4. Have CD branches: dev/qa/staging/master
 >5. Use semantic versioning and persist with git tags
 >6. Promote app version tags to CD branches, so we know what is in that lane
 >7. Have the CI/CD github actions templatized, where new projects just need to configure input files
 >
 >
 >![image.png](https://images.zenhubusercontent.com/623b9450b52d5c969dd04278/3f65d220-7e77-4fcc-9daf-71787104c575)

#### Labels: Epic ops 
---
Linked Issues: `2`
<p>
<table>
<tr><th>Est</th><th>Act</th><th>Type</th><th>Title</th><th>Labels</th><th>Status</th><th>Link</th></tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>CI Rework</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/149">zenhub-dev/#149</a></td> </tr>
<tr><td>+8</td><td>+8</td><td>Issue</td><td>CD Rework</td><td>ops </td><td>:heavy_check_mark:closed</td><td><a href="https://github.com/OnboardRS/zenhub-dev/issues/150">zenhub-dev/#150</a></td> </tr>
</table>
</p>


### `Epic` - Test cluster node resizing's effect on cluster stability. - `0`:`0` pts. - :heavy_check_mark:closed - [zenhub-dev/#120](https://github.com/OnboardRS/zenhub-dev/issues/120)


 > Cluster currently runs on T3 mediums in dev and staging, and T3 larges in prod.
 >CPU availability continues to be an issue, need to explore M or C series compute.
 >Launch a fully deployed and functionity replica of dev in sandbox and then change the instance size of the ASG.

#### Labels: Epic ops 
---

