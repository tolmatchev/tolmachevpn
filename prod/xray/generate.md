To generate `uuid`

```bash
docker compose run --rm xray xray uuid
```

To generate `PrivateKey` and `Password (PublicKey)`
```bash
docker compose run --rm xray xray x25519
```

to generate `sid`
```bash
openssl rand -hex 8
```