# contract-intelligence-demo-pages

Hosting repo for the lumif.ai contract intelligence interactive demo.

**This repo contains only the encrypted single-file bundle.** Source code, fixtures, and unencrypted artifacts live in the private source repo `Lumif-ai/contract-intelligence-demo`.

## Live URL

https://lumif-ai.github.io/contract-intelligence-demo-pages/

Password-protected via StatiCrypt (AES-256, client-side decrypt). Password is shared out-of-band with the Lumif-ai team and named prospects.

## How updates happen

The source repo's GitHub Action rebuilds the demo, re-encrypts with the current password, and pushes the new `index.html` here on every commit to `main`.

Do not commit directly to this repo — your change will be overwritten on the next source-repo push.
