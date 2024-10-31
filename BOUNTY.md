# Parse Bounty Program

The goal of the Parse Bounty Program is to facilitate product development by recycling community donations back into the contributor community and making paid contributions more accessible to the community.

An open issue can have a bounty assigned to it, for which the contributor(s) can apply for compensation once their pull request has been merged. For GitHub issues, the bounty is indicated in the form of a bounty label. For example, a bounty label indicating a US$10.00 compensation has the format “bounty:$10”. The compensation is indicated in U.S. Dollars.

## Process

1. A contributor picks an issue with a bounty
2. The contributor submits a pull request
3. A reviewer gives feedback and the contributor resolves any corrections
4. A reviewer merges the pull request
5. The contributor submits an [expense claim](https://opencollective.com/parse-server/expenses/new) via the Open Collective that includes:
   - GitHub user ID
   - URL to the closed GitHub issue
   - URL to the merged GitHub pull request
6. A reviewer asks the contributor on GitHub to confirm that they submitted the claim to link the OC user to the GitHub user
7. The contributor confirms the correctness of the claim
8. The PMC approves the payout
9. The Open Collective processes the payout

When working on an issue, the contributor is encouraged to post an issue comment to signal to other contributors that they are working on it. This is not binding for other contributors, and they may also start to work on the issue, but it should help to prevent multiple contributors from working on the same issue without coordinating.

A contributor is not required to request a bounty when fixing an issue that has a bounty assigned to it. By not claiming the bounty, the contributor effectively re-donates the bounty to the community funds.

## Conditions

The contributor must have an email address published in their GitHub profile, which will be used for communication regarding the payout. This is required to prevent someone from claiming the bounty of another contributor.

The contributor has 90 days to request compensation for a bounty and provide all required information. After 90 days the contributor forfeits the bounty. A contributor cannot submit more than one bounty request form per calendar month, they may however correct the form after submission and before the PMC approves the payout.

The decision to assign a bounty to an issue or revoke a bounty from an issue is made by the Project Management Committee (PMC). If a bounty is revoked, while a contributor has been actively working on a pull request, the PMC may decide to compensate the contributor not for the full bounty but an aliquot portion of the bounty according to the code committed to the pull request on GitHub at the time the bounty is revoked.

If multiple contributors work as a team on the same issue or pull request in a self-coordinated manner, we expect the contributors to decide for themselves how to split the bounty among them. If the team cannot resolve the issue, the Project Management Committee will make a decision on how to split the bounty among team members, based on their best judgement from code and comments of the contribution concerned.

If multiple contributors work on the same issue but different pull requests in a non-coordinated manner, and they all claim the same bounty, the bounty will be awarded to the contributor whose pull request has been merged. The decision which pull request to merge will be determined by time, completeness and code quality. We want to avoid such race scenarios where contributors do not get compensated for their effort, and more importantly, their effort was in vain while it could have been invested into other open issues. Therefore we strongly encourage contributors to coordinate and distribute issues among themselves.

The compensation is provided by Parse Platform as a voluntary token of gratitude. Receiving compensation on an irregular or regular basis shall not establish or constitute any form of a financially compensated relationship of employment between Parse Platform and the contributor. Contributing under the program does not give the contributor any rights to compensation. Even if a bounty label is applied to an issue, Parse Platform may refuse to compensate the contributor if it deems necessary to do so, for example if a label has been applied by mistake, or the bounty value has been set incorrectly by mistake, or in unforeseen circumstances to maintain the financial integrity of Parse Platform.

## Sponsored Bounty

A bounty can be sponsored by a 3rd party who provides the funding for the development of a specific feature or bug fix. The funding is provided in the form of a donation to the Parse Platform Open Collective. After the donation, the bounty will be assigned to the specific GitHub issue for at least 3 months. The bounty amount can be increased over time if necessary to attract more attention, but it cannot be decreased. When increasing the bounty amount, the time period resets and restarts from the time of the additional donation. After the time period, the bounty may be removed from the GitHub issue and the donation becomes a general donation to Parse Platform. Donations are non-refundable, also in case the issue is not picked up by any developer.

Parse Platform does not manage the development of a sponsored bounty, it only provides the forum to advertise the sponsorship. It is up to the sponsor to pick the developer(s) it wants to work with and how to divide the bounty among the developers in case multiples developers are chosen. Parse Platform does not assume any responsibility for scope, quality, time or viability of the developed work. Parse Platform will review and steer the development as it deems necessary to ensure that the final development result is fit for merging into the open source code base. The work created during a sponsored development is an open source contribution under the license of the respective GitHub repository.

A sponsored bounty comes with additional services depending on the bounty amount. The following table shows the available amounts for sponsored bounties, the required donation and the services provided.

| Bounty    | Donation         | GitHub Tag <sup>(1)</sup> | Release Note <sup>(2)</sup> | Social Media Post <sup>(3)</sup> |
|-----------|------------------|---------------------------|-----------------------------|----------------------------------|
| 100 USD   | 150 USD (+50%)   | ✅                         | ✖️                           | ✖️                               |
| 250 USD   | 375 USD (+50%)   | ✅                         | ✅                           | ✖️                               |
| 500 USD   | 700 USD (+40%)   | ✅                         | ✅                           | ✅                                |
| 750 USD   | 975 USD (+30%)   | ✅                         | ✅                           | ✅                                |
| 1,000 USD | 1,250 USD (+25%) | ✅                         | ✅                           | ✅                                |
| 2,000 USD | 2,400 USD (+20%) | ✅                         | ✅                           | ✅                                |

<sup>(1)</sup> A sponsorship tag will be added to the GitHub issue to advertise the bounty to developers. <sup>(2)</sup> The release notes entry will contain a sponsorship note. <sup>(3)</sup> The sponsorship will be advertised on our social media to attract more developers.
