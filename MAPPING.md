# OMDY Protos — Slug + Image Mapping (v4)

Deployed: 2026-05-23 — humane slugs replace `lead_20260412_XXX/` paths, and `/assets/placeholder-*.jpg` references swap to verified Unsplash CDN URLs.

## Slug map

| Lead ID | Slug | Business | Tier |
|---|---|---|---|
| lead_20260412_001 | `ksar-essaoussan` | Restaurant Ksar Essaoussan | restaurant_standard |
| lead_20260412_002 | `dar-zitoun` | Restaurant Dar Zitoun | restaurant_standard |
| lead_20260412_003 | `cafe-atlas` | Cafe Restaurant Atlas | restaurant_standard |
| lead_20260412_004 | `chez-driss` | Restaurant Chez Driss | restaurant_haut_gamme |
| lead_20260412_005 | `pizzeria-venezia` | Pizzeria Venezia | restaurant_standard |
| lead_20260412_006 | `nomad` | Restaurant Nomad | restaurant_haut_gamme |
| lead_20260412_007 | `terrasse-des-epices` | Restaurant Terrasse des Epices | restaurant_haut_gamme |
| lead_20260412_008 | `al-fassia-gueliz` | Restaurant Al Fassia Gueliz | restaurant_haut_gamme |
| lead_20260412_010 | `argana` | Restaurant Argana | restaurant_haut_gamme |

> L'Mida (lead_20260412_009) is intentionally out-of-scope.

## Image mapping (Unsplash photo IDs, all verified HTTP 200)

| Slug | Hero (w=1600) | About (w=1200) |
|---|---|---|
| ksar-essaoussan | `1577906096429-f73c2c312435` | `1473093295043-cdd812d0e601` |
| dar-zitoun | `1592861956120-e524fc739696` | `1546069901-ba9599a7e63c` |
| cafe-atlas | `1555992336-fb0d29498b13` | `1467003909585-2f8a72700288` |
| chez-driss | `1414235077428-338989a2e8c0` | `1552566626-52f8b828add9` |
| pizzeria-venezia | `1513104890138-7c749659a591` | `1574071318508-1cdbab80d002` |
| nomad | `1517248135467-4c7edcad34c4` | `1559339352-11d035aa65de` |
| terrasse-des-epices | `1466978913421-dad2ebd01d17` | `1606787366850-de6330128bfc` |
| al-fassia-gueliz | `1424847651672-bf20a4b0982b` | `1540189549336-e6e99c3679fe` |
| argana | `1504674900247-0877df9cc836` | `1546833999-b9f581a1996d` |

URL template: `https://images.unsplash.com/photo-<ID>?w=<WIDTH>&q=80&auto=format&fit=crop`
