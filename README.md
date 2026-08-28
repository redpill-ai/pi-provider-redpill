# pi-provider-redpill

> [!WARNING]
> This repository is a legacy generated artifact and is no longer the supported installation source.

Install the current RedPill provider from npm:

```bash
pi install npm:pi-provider-redpill
pi
```

Then use Pi's native flows:

```text
/login redpill
# enter your RedPill API key and wait for aci-verified
/model
# search for redpill/, choose a model, then press Ctrl+S to save it
```

Pi persists credentials, the live model catalog, and the saved default model. For one process, you
can set `REDPILL_AI_API_KEY` instead.

Attestation is verified before model traffic. Every response receipt and cited session is verified
before Pi completes the turn. The `/redpill-attestation`, `/redpill-receipts`, `/redpill-receipt`,
and `/redpill-session` commands inspect the same enforced provider state.

The maintained source is
[`clients/pi-provider/packages/pi-provider-redpill`](https://github.com/Dstack-TEE/private-ai-gateway/tree/main/clients/pi-provider/packages/pi-provider-redpill)
in [`Dstack-TEE/private-ai-gateway`](https://github.com/Dstack-TEE/private-ai-gateway). File issues and
code changes there. The published package is
[`pi-provider-redpill`](https://www.npmjs.com/package/pi-provider-redpill).
