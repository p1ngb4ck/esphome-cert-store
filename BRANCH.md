# `pr/cert-store`

One part of the topic repo p1ngb4ck/esphome-cert-store. The whole topic, with its description, is the branch `main`.

Change of this branch: `cert_store`: CA, client certificate and key per TLS client - embedded, from a storage, or by name from a folder, Home Assistant or HTTP sources; the CA bundle as fallback

Based on these branches, whose changes it holds and builds on:

- `pr/esp32-cert-bundle-sha512` of p1ngb4ck/esphome-esp32-platform: the certificate bundle keeps SHA-384 / SHA-512
- `pr/storage` of p1ngb4ck/esphome-storage-interface: the `storage` component: registry, path / filesystem / network / raw storages, the asynchronous worker (jobs, streams), `storage.*` actions, PSRAM transfer buffer, change feed, ISO 9660 mount
