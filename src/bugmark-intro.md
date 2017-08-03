# Bugmark

A market platform for experimenting with capital incentives and peer production.

| Team        |                                                   |
|---------------------|----------------------------------------------------------|
| Malvika Rao    | Research Lead |
| Andy Leak | Lead Developer                           |
| Rich Bodo       | Developer                             |
| Zvi Boshernitzan | Developer                                             |

---

## Use Case: Simple Reward

> "I'll bet $10 that no one fixes issue #2 by 1/1/18"

Same as a bug bounty.  Straight odds.  Only whole bids can be taken.

Also used for things like feature poker.


---

## Reward Data: Simple Reward

|   Reward Match Params    |                                                   |
|---------------------|----------------------------------------------------------|
| Repository    | Selected prior in UI |
| Issue Number | 2             |
| Expiry       |  1/1/18                      |
| Issue Status |   Closed                                     |



---

## Bid Data: Simple Reward

|   Publisher Bid Attributes     |                                                   |
|---------------------|----------------------------------------------------------|
| Publisher   | ID of person making the prediction |
| Amount | 10             |

When an opposite counterparty bid is created, the market makes a deal.

---

## Use Case: Simple Forecast

> "I'll bet $10 that a CVE bug is found in this library by 1/1/18"

No bug number in the attributes.  CVE database instead of a repo.

Provides intelligence even if no counterparty.  

---

### Advanced Features I

* Tradable Contracts:
A bid can be wrapped in ERC20 so it can be resold.

* Derivatives:
Packaging of tradeable contracts for secondary markets.

---

### Advanced Features II

* Odds:
> "I'll pay 10 if it's fixed today, you pay 100 if it isn't."

* Payout Algorithms:
Net0, Net30, 12 equal monthly installments, Bug Subsumption.

---

### Advanced Features III

* Specified Parties:
> "I'll pay 10 if Joe Blow fixes bug #2 by 1/1/18"

* Counter-Offers:
Alert publisher of counter-offer, close out old bid if he takes it.

---

## Secondary Use Cases: Arbitrage

Ex: Sam is a project manager with a big rolodex of developers.

Sam makes counterparty bids on a large number of rewards, and hires developers as needed in her locale to close the issues.

---

## Secondary Use Cases: Bots

Automatically:

* Bid on bugs that create high support costs.
* Invest in open source projects that your business depends on.

---

## Secondary Use Cases: Secondary Markets

Verifiable, immutable data is suitable for secondary markets.  Those markets can also provide intelligence.

> "I bet $10 that every issue in which Bob is counterparty to a reward this year gets closed."

> "I bet $10 that new_contributor_count is directly proportional to bids countered this month."

---

## Many more

Check out user stories, or add some - here:

https://github.com/mvscorg/bugmark/wiki/Dapp-Design#user-stories
