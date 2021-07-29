# Zcash Features

This is a quick summary; the Zcash technology page has additional information and examples.

Primary features:

- *Addresses*: Zcash has two types of addresses: private (z-addresses) and transparent (t-addresses). Z-addresses start with a “z,” and t-addresses start with a “t.” The two Zcash address types are interoperable. Funds can be transferred between z-addresses and t-addresses. There are privacy implications of shielding or deshielding information through these transactions. Today, most wallets and exchanges exclusively support t-addresses, although support for shielded addresses is available for mobile and desktop wallets.
- *Transactions*: Transactions between two transparent addresses (t-addresses) work just like Bitcoin: the sender, receiver and transaction value are publicly visible. Transactions involving shielded addresses include shielded (z-to-z), shielding (t-to-z), and deshielding (z-to-t), with the z-address getting privacy protections. The most secure transaction is a shielded (z-to-z) one, which encrypts the sender and receiver addresses and transaction amount. However, all transactions appear on the public blockchain, so a transaction is known to have occured and what fees were paid.
- *Viewing keys*: The owner of a z-address can share its transaction details with trusted third parties via a view key–a key that grants read access but not spend authority over the address. This allows for “selective disclosure”, where transactions are auditable but disclosure is under the participant’s control. This allows compliance with payment for auditing, tax regulations, or anti-money laundering rules.
