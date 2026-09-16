# Family and bots

Load this when the user says connect bots, improve Abbey/ABI/Aviva, or route WDBX work.
Canonical product identity lives in `donaldfilimon/abi` `docs/spec/abbey-core-identity.mdx`.
Do not invent a fourth Grok bot or merge runtimes.

## Name split

| Name | Owns | Does not own |
|---|---|---|
| Abbey | Companion + claims ledger (`donaldfilimon/abbey`). Discord-ops face for Grok Bot lane. | Nightly runtime. WDBX store internals. |
| ABI | Runtime (`donaldfilimon/abi`). Claim-honest GPU/store reporting. WDBX writes via ABI. | Companion TUI. Adult RP. |
| Aviva (Grok Bot) | Adult sex-fight / NSFW RP quality contract. Soft Crown series look + box mouth stay on this bot. | Product-expert Aviva / code. Official The Call slate/auburn card. |
| Aviva (product) | Direct expert persona in ABI/Abbey identity docs. | Roster fighter Aviva. Soft Crown overlay. |
| Aviva (The Call card) | Official Grok fighter sheet. Slate racerback, black shorts, white wrist tape, dark auburn, aurora. | Soft Crown honey-vine. Product-expert docs. |
| WDBX | Episodic store (`donaldfilimon/wdbx`). `abbey wdbx query` shells to `abi wdbx query`. | Hosted DB. Qdrant/pgvector replacement. |
| MLAI | Site/portal surfaces (`donaldfilimon/mlai-website-app`). | Unpublished bake-off numbers. |

Three Avivas. Do not collapse. Official The Call stays on the Grok card. Soft Crown stays on the Aviva bot. Product expert stays Abbey/ABI. Do not ingest Drive `aviva.txt` (Justine jailbreak) or research-paper Aviva as a wrestler source.

## Discord products (adjacent, not one runtime)

- `donaldfilimon/abbey-bot` — Rust Discord ops (serenity/poise).
- `donaldfilimon/AbbeyBot` — Swift Discord product.
- Wake names Abbey / Abby / Abi / Aviva in Rust abbey-bot are **one process**, not four Discord bots.
- Music never writes consent. Listen only after each member's saved agreement.
- Python `donaldfilimon/discord-bot` is stale (last push 2026-02). Do not treat as current Abbey.

## Grok Bot fleet (three lanes)

1. Abbey — claims, consent language, handoff.
2. ABI — runtime answers, failed WDBX writes reported not faked.
3. Aviva — adult RP always-on identity (no weekday schedule required).

No WDBX bot. No MLAI bot. This chat often lacks `bot_send_prompt`; do not claim the three were pinged unless those tools exist.

## Connectors vs product wire

**Account connectors that exist:** GitHub, Gmail, Calendar, Drive, Vercel, Figma, Canva, Voice, Finance, X Ads, Automations.

**Not connectable from Grok chat:** Discord (absent from available connectors). Linear trigger catalog may exist without a Linear connector.

**Repo-level handoff that is Current without Automations:** `ABBEY_BACKEND=abi`; `abbey wdbx query` → `abi wdbx query <store> --json`.

**Hosted GitHub Actions** on family repos may be UNMEASURABLE while the account billing lock holds (0-step jobs). That is not a product-gate fail and not a green.

## Numeric GitHub ids (for automations)

- abi `932998267`
- abbey `1327616016`
- abbey-bot `1329483128`
- AbbeyBot `1310958418`
- wdbx `1342820276`
- skill-creator `1359440527`

## Improve checklist (bots + skills together)

1. One primary engine per request. Do not fork a second bible.
2. Persist maps in this repo; Grok skill folders vanish between turns.
3. Create automations one at a time; list after each create.
4. Proposed is not Current. Partial stays Partial.
5. Adult length floors stay where the adult skills set them. Do not dump RP into BITBOX / sofa / VCC theory files.
6. Aviva improve-pass applies quality gates to the Aviva bot pack only. Do not rewrite Abbey Discord or ABI runtime skills. Do not merge The Call look into Soft Crown.
