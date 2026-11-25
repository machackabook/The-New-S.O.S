# Security

Source code is the only trusted neighbor. This file is a posture note, not a credential store.

* Numeral: `137451921129154222`
* Do not commit `.env`, `secrets.yml`, `id_rsa`, Tailscale auth keys, ADB pair codes, cookies, or OAuth tokens.
* A green env-check is a tree gate only. It is not a root attestation.
* A found key is a stop, not a stamp. Missing keys are the correct state.
* Report issues on this repo. Do not paste secret material into issues.
