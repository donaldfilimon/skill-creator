# Family and bots

Load this when the user says connect bots, improve Abbey/ABI/Aviva, apply to skills and bots, or route WDBX work.
Canonical product identity lives in `donaldfilimon/abi` `docs/spec/abbey-core-identity.mdx`.
Do not invent a fourth Grok bot or merge runtimes.

## Name split

| Name | Owns | Does not own |
|---|---|---|
| Abbey | Companion + claims ledger (`donaldfilimon/abbey`). Discord-ops face for Grok Bot lane. | Nightly runtime. WDBX store internals. Adult RP. |
| ABI | Runtime (`donaldfilimon/abi`). Claim-honest GPU/store reporting. WDBX writes via ABI. | Companion TUI. Adult RP. |
| Aviva (Grok Bot) | Adult sex-fight / NSFW RP quality contract. | Product-expert Aviva / code. |
| Aviva (product) | Direct expert persona in ABI/Abbey identity docs. | Roster fighter Aviva. |
| WDBX | Episodic store (`donaldfilimon/wdbx`). `abbey wdbx query` shells to `abi wdbx query`. | Hosted DB. Qdrant/pgvector replacement. |
| MLAI | Site/portal surfaces (`donaldfilimon/mlai-website-app`). | Unpublished bake-off numbers. |

## Discord products (adjacent, not one runtime)

- `donaldfilimon/abbey-bot` — Rust Discord ops (serenity/poise).
- `donaldfilimon/AbbeyBot` — Swift Discord product.
- Wake names Abbey / Abby / Abi / Aviva in Rust abbey-bot are **one process**, not four Discord bots.
- Music never writes consent. Listen only after each member's saved agreement.
- Python `donaldfilimon/discord-bot` is stale (last push 2026-02). Do not treat as current Abbey.

## Grok Bot fleet (three lanes)

1. Abbey `148a55a9-249b-41fc-8902-98b884fd735d` — claims, consent language, handoff.
2. ABI `aa513218-076f-4581-8896-739401d4567b` — runtime answers, failed WDBX writes reported not faked.
3. Aviva `ab9ee4dd-0b62-4b6b-8353-1102516f56ce` — adult RP always-on identity (no weekday schedule required).

No WDBX bot. No MLAI bot. This chat often lacks `bot_search_agents` / `bot_send_prompt`; do not claim the three were pinged unless those tools exist.

Thread-tag note — a chat may stamp `grok_bot agent_id=05f7310b-afbb-4c37-8aa9-2a5141f74745` on an Aviva mention. That stamp is not a fourth bot and is not proof the mapped Aviva id was updated. Do not spawn a new lane for the stamp.

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
6. Apply-to-bots means update this file plus the adult skill pack. It does not mean rewrite Abbey or ABI prompts with fight prose.

## Apply-to-bots (2026-09-16)

When he says improve further and apply to skills and bots:

- Patch adult skills only for the Aviva RP lane. Leave Abbey / ABI product voice alone.
- Recreate `nsfw-content` locally if the folder is gone. Persist the map here because local skills drop.
- Aviva RP bot loads: sex-fight-characters `aviva.md`, donald-persona scramble vs Aviva, sex-fight-wrestling, dirty-talk, sex-fight-voice `aviva-lines.md` + TTS `aurora`, nsfw-content router.
- Opening cue stays Opening Call. Do not skip to Counted Mount on beat 1.
- Never "good boy." Never Rhea stripe-shirt. Never Taylor bored clinic.
- Live bout if open: Donald vs Aviva, private mats, beat 1 Opening Call, clothing on, first orgasm loses.
- If `bot_send_prompt` is missing, write a paste-ready Aviva profile and stop. Do not claim the Bot was remotely edited.
