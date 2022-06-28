# L3
The Bitcoin Lightning Network makes it nearly trivial to add new economic interactions to all kinds of applications using real money. The easiest way to provide such features is by use of a custodial micro-wallet managed by the app itself, on top of a well-provisioned lightning node that backs it. However, implementing an accounting ledger for a large number of users is non-trivial, and critical for the integrity of the experience (since all funds are being commingled in the node on the backend).

**L**ocal **L**ightning **L**edger (L3) implements a simple ledger system you can include in your nodejs web applications, so you can focus on interactions, not accounting.
