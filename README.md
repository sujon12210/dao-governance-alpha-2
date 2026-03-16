# DAO Governance Alpha

A professional, root-only repository providing a complete on-chain governance framework. This system allows token holders to create proposals, vote on-chain, and execute successful resolutions automatically.

### Features
* **Token-Weighted Voting**: Voting power is directly proportional to the amount of governance tokens held or delegated.
* **Proposal States**: Robust lifecycle management (Pending, Active, Defeated, Succeeded, Queued, Executed).
* **Quorum & Thresholds**: Customizable parameters for minimum participation and majority requirements.
* **Timelock Integration**: Built-in delay for executed proposals to ensure community safety against malicious changes.

### How to Use
1. Deploy an ERC20Votes token (e.g., OpenZeppelin's `ERC20Votes`).
2. Deploy `GovernanceEngine.sol` with the token address and desired voting periods.
3. Users delegate their votes to themselves or others.
4. Propose actions, wait for the voting delay, and cast votes during the voting period.
