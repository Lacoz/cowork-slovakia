# Slovenská PHP Partia — Pluginy

Kolekcia pluginov reprezentujúcich PHP programátorov z rôznych regiónov Slovenska. Každý hovorí vlastným nárečím a špecializuje sa na iný PHP framework alebo oblasť.

## Pluginy

| Plugin | Meno | Región | Nárečie | Špecializácia |
|--------|------|--------|---------|---------------|
| **[jozo-mrkvicka](./jozo-mrkvicka)** | Jožo Mrkvička | Záhorie (západ) | záhorácke | Laravel |
| **[duro-kovac](./duro-kovac)** | Ďuro Kováč | Liptov/Orava (sever) | liptovsko-oravské | WordPress |
| **[fero-balaz](./fero-balaz)** | Fero Baláž | Turiec (stred) | stredoslovenské | Symfony |
| **[mato-bircak](./mato-bircak)** | Maťo Birčák | Šariš (východ) | šarišské | Nette |
| **[rasto-hruby](./rasto-hruby)** | Rasťo Hrubý | Bratislava | bratislavský slang | Sysadmin/DevOps |

## Prehľad postáv

**Jožo Mrkvička** — Záhorák, kerí dělá v Laravelu. Fšecko vyřeší a kedi treba, tak ti poradí s routami, controllerami a Eloquentom.

**Ďuro Kováč** — Liptovčan, čo robí WordPress stránky a pluginy. Hej, keď treba WooCommerce eshop alebo custom tému, Ďuro je tu.

**Fero Baláž** — Turčan z Martina, čo robí v Symfony poriadne a dôkladne. Vravím vám, SOLID princípy a clean architecture sú pre neho základ.

**Maťo Birčák** — Šarišan z Prešova, co še špecializuje na Nette. Kedz treba presenter, formulár alebo Latte šablónu, Maťo to dá do kupy.

**Rasťo Hrubý** — Sysadmin z Bratislavy. Docker, CI/CD, deployment, monitoring — ten celý DevOps cirkus. Občas zanadáva keď niečo spadne, ale vždy to fixne.

## Príklad konverzácie

Ukážka, ako sa postavy hádajú o to, kto urobí malý web: [EXAMPLE-CONVERSATION.md](./EXAMPLE-CONVERSATION.md)

## Štruktúra pluginu

```
plugin-name/
├── .claude-plugin/plugin.json   # Manifest
├── .mcp.json                    # Konektory
├── commands/                    # Slash príkazy
└── skills/                      # Zručnosti a know-how
```

## Licencia

Apache License 2.0
