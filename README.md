The configuration code for the [trustee timeline graphic](https://society-rse.org/about/governance/trustee-timeline/).

## Updating the Timeline
To update the timeline, you should only need to do the following:
1. Add the date of the most recent AGM, i.e. `var agm_2024 = new Date("2024-09-04");`
2. Add the current new trustees to a new section inside the `trustees` array.
     - Make sure to add the correct start/end date for each trustee's tenure.
3. Update the role chart for the President, Vice-President, Treasurer, Vice-Treasurer and Secretary roles.

## Pull Request
We recommend you follow software engineering best practice and make the changes on a new branch before creating a pull request.
Ideally, a member of the governance team should approve the pull request (and check names/dates) before merging.

## Deployment
When the changes are merged onto the main branch, the updated timeline will automatically be deployed.
- The page is hosted here: https://socrse.github.io/trustee-timeline/.  
- It is embedded on this page of the Society website: https://society-rse.org/about/governance/trustee-timeline/
