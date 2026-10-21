# Character Card Checker

A free, open-source tool for reading, checking and converting AI character cards.

**Use it online:** https://roleplayadotcom.github.io/character-card-checker/

Drop in a character card and it shows you what is inside, checks it against the V2 and V3 card specs, and lets you download it as a clean V2 or V3 JSON file.

## What it reads

- **PNG cards** with the character stored in the `chara` (V2) or `ccv3` (V3) chunk
- **JSON cards** in V1, V2 (`chara_card_v2`) or V3 (`chara_card_v3`) format
- Cards exported from Janitor AI, Chub, SillyTavern, RisuAI, Agnaistic and most other apps that follow the spec

## What it checks

- Name, description, personality, scenario and first message
- Alternate greetings, example dialogue, tags and creator
- Lorebook (character book) entries
- Common problems: missing first message, very short or very long descriptions, old V1 format, missing tags

## Privacy

Everything runs in your browser. Your card is never uploaded anywhere.

## Using your card

Cards checked here import directly into [RolePlaya](https://roleplaya.com), the AI roleplay platform for adults (18+), along with most other card-compatible apps. See [how to import Janitor, Chub and SillyTavern cards](https://roleplaya.com/blog/import-janitor-chub-sillytavern-cards/).

## Related

- [Character Card Maker](https://roleplayadotcom.github.io/character-card-maker/): create or edit a card and download it as PNG or JSON

## Licence

MIT. Free to use, copy and change.
