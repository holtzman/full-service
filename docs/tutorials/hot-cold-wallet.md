---
description: How to use full service with offline wallets
---
- a full service wallet contains two private keys: view key and spend key
- you can run full service offline to maintian a "cold" wallet. This wallet will have access to both view and spend keys.
- you can run full service online with only the private-view key. This wallet will be able to view transactions that belong to the wallet, but it will not know whether or not those transactions have been spent. If you want the view-only account balance to reflect spent transactions, you can manually mark transactions as spent using (the mark tx as spent endpoint).
- You can build transactions on an offline machine and then submit them with an online machine. You can do this in two ways:
- upload the ledger to the offline machine and use it to build a transaction (details with endpoints here)
- export txos from a view-only wallet

- ledger validator node