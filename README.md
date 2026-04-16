# BSV Sweep Tool

A single-file browser tool for sweeping all BSV from one address to another.

Open `bsv-sweep.html` directly in a browser — no install, no server. Enter a private key (WIF or hex), a destination address, preview the transaction, and broadcast it.

The private key never leaves the browser. UTXOs are fetched from the WhatsOnChain API, the transaction is built and signed client-side using `@bsv/sdk`, then broadcast via the same API.
