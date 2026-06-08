# sc-ero — Allegro Marketplace Integration

This page exists to satisfy Allegro's [custom `User-Agent` policy](https://developer.allegro.pl/news/do-konca-czerwca-2026-zaimplementuj-wlasny-niestandardowy-identyfikator-user-agent-w-twojej-aplikacji-q0K2EbxgXCg)
([tracking issue #13126](https://github.com/allegro/allegro-api/issues/13126)). It lets
Allegro identify and contact the operator of the integration that sends the User-Agent:

```
sc-ero/<version> (+https://igorfurman.github.io/sc-ero-allegro-info/)
```

## About the application

**sc-ero** is a private integration that synchronizes product stock, pricing, and order
fulfillment between supplier systems and the Allegro marketplace via the Allegro REST API.
It runs automated catalog stock/price sync and order processing, and respects Allegro's
published rate limits.

| Field | Value |
| --- | --- |
| **Application name (Allegro)** | `sc-ero` |
| **Purpose** | Automated catalog stock/price synchronization and order fulfillment via the Allegro REST API |
| **Operator contact** | miberoshop@gmail.com |
| **Last updated** | 2026-06-08 |

## Operator contact

For deprecations, abuse reports, or policy questions regarding this integration, contact:

**miberoshop@gmail.com**

---

_This page contains no secrets, tokens, or credentials. It is intentionally public and
permanent so the `User-Agent` info URL remains resolvable._
