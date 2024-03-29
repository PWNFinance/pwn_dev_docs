# Off-chain signed offer

## 1. Summary

Off-chain offer negotiation enables borrowers to signal a desire to take a loan without executing an on-chain transaction.&#x20;

That means on-chain transactions are executed only when the borrower and lender agree on the loan terms. Or if a lender decides to step back from an offer they made.

{% hint style="info" %}
Note that this feature can be used not only by [Externally Owned Accounts](https://www.coingecko.com/en/glossary/externally-owned-accounts-eoa) but also by smart contract wallets which implement [EIP-1271](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1271.md).
{% endhint %}

## 2. User flow diagrams

#### Simplified user flow with off-chain offers

![](<../../../.gitbook/assets/PWN\_contracts-Offchain offer user flow.drawio (1).png>)

#### Complete user flow with off-chain offers

![](<../../../.gitbook/assets/pwn-flow (1)-Flow v2.drawio.png>)
