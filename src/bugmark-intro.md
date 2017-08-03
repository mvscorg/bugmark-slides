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

|   Reward Attributes    |                                                   |
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

|   Counterparty Bid Attributes   |                                                   |
|---------------------|----------------------------------------------------------|
| Counterparty   | ID of person taking the other side |
| Amount | 10             |

These bids match so the market makes a deal.

---

## Use Case: Simple Forecast

> "I'll bet $10 that a CVE bug is found in this library by 1/1/18"

No bug number in the attributes.  CVE database instead of a repo.

---

## Use Case: 
