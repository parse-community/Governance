# Voting

Every member of the community, from interested user to the most active developer, has a vote. The project encourages all members to express their opinions in all discussion and all votes. However, only the PMC members have binding votes for the purposes of decision making. They do this by selecting on of the options below in the relevant poll:

- `+1` ‘yes’, ‘agree’: also willing to help bring about the proposed action
- `+0` ‘yes’, ‘agree’: not willing or able to help bring about the proposed action
- `-0` ‘no’, ‘disagree’: but will not oppose the action’s going forward
- `-1` ‘no’, ‘disagree’: opposes the action’s going forward and must propose an alternative action to address the issue (or a justification for not addressing the issue)

To abstain from the vote, participants simply do not respond. However, it can be more helpful to cast a `+0` or `-0` than to abstain, since this allows the team to gauge the general feeling of the community if the proposal should be controversial.

It is the responsibility of the PMC members to ensure that the opinions of all community members are considered. While not all members may have a binding vote, a well-justified `-1` from a non-committer must be considered by the community, and if appropriate, supported by a binding `-1`.

A `-1` can also indicate a veto, depending on the type of vote and who is using it. Someone without a binding vote cannot veto a proposal, so in their case a `-1` would simply indicate an objection.

When a vote receives a `-1`, the community must address the objection. Such discussion will continue until the objection is either rescinded, overruled (in the case of a non-binding veto) or the proposal itself is altered in order to achieve consensus (possibly by withdrawing it altogether). In the rare circumstance that consensus cannot be achieved, the PMC will decide the forward course of action.

## Types Of Approval

Different actions require different types of approval, these are summarised in the table below.

| Type                | Description                                                                                                                                                                                                                                                                                                                                                                                                      | Duration  |
|:--------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------:|
| Lazy consensus      | An action with lazy consensus is implicitly allowed, unless a binding -1 vote is received. Depending on the type of action, a vote will then be called. Note that even though a binding -1 is required to prevent the action, all community members are encouraged to cast a -1 vote with supporting argument. Committers are expected to evaluate the argument and, if necessary, support it with a binding -1. | N/A       |
| Lazy majority       |	A lazy majority vote requires more binding +1 votes than binding -1 votes.	                                                                                                                                                                                                                                                                                                                                     | 72 hours  |
| Consensus approval  |	Consensus approval requires three binding +1 votes and no binding -1 votes.                                                                                                                                                                                                                                                                                                                                      | 72 hours  |
| Unanimous consensus |	All of the binding votes that are cast are to be +1 and there can be no binding vetoes (-1).                                                                                                                                                                                                                                                                                                                     | 120 hours |
| 2/3 majority        |	Some strategic actions require a 2/3 majority of PMC members; in addition, 2/3 of the binding votes cast must be +1. Such actions typically affect the foundation of the project (e.g. adopting a new codebase to replace an existing product).                                                                                                                                                                  | 120 hours |

## When is a Vote Required?

Every effort is made to allow the majority of decisions to be taken through lazy consensus. That is, simply stating one’s intentions is assumed to be enough to proceed, unless an objection is raised. However, some activities require a more formal approval process in order to ensure fully transparent decision making.

The table below describes some of the actions that will require a vote and which type should be used.

| Action             | Description                                                                                    | Approval type                        |
|--------------------|------------------------------------------------------------------------------------------------|--------------------------------------|
| Release plan       | Defines the timetable and actions for a release. A release plan cannot be vetoed.              | Lazy majority                        |
| Product release    | When a release is ready, a vote is required to accept the release. A release cannot be vetoed. | Lazy majority                        |
| New committer	     | A new committer has been proposed.                                                             | Consensus approval of the PMC        |
| New PMC member     | A new PMC member has been proposed.                                           	                | Consensus approval of the community  |
| Committer removal  | When removal of commit privileges is sought.                                                   | Unanimous consensus of the PMC       |
| PMC member removal | When removal of PMC membership is sought.                                                      | Unanimous consensus of the community |
