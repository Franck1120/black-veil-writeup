# Black Veil — Publishing Metadata

## Title alternatives

1. **Black Veil: A Field-Deployable Crypto Puzzle Over Meshtastic** *(current — clear, keyword-rich)*
2. The Broadcast Trap: Teaching Mesh Networking With a Vigenère Cipher in the Woods
3. One Argument Away From Failure: A LoRa Crypto Puzzle Where `destinationId` Was the Whole Objective
4. Ghost Frequency: I Built a Cryptography Challenge on a Meshtastic Mesh — Here's the Design
5. Field Crypto Under Stress: Designing a Hand-Solvable Cipher for a 50-Player Milsim

## One-line teaser

> I hid a Vigenère key across three documents and made "send it to one node, not the whole mesh" the win condition — here's the full design of a LoRa crypto puzzle that ran in the field.

## SEO description (160 char)

> Designing a field-deployable Meshtastic/LoRa crypto puzzle: Vigenère key assembly, broadcast-vs-direct-message as the win condition, and an honest post-mortem.

*(154 characters)*

## Suggested tags

**Reddit**
- r/meshtastic — `Project`, `Showcase`
- r/cryptography — `Educational` *(lead with the Vigenère key-assembly design, not the airsoft framing — that sub is strict about substance)*
- r/airsoft — `Milsim`, `Game Design`
- r/LoRa — `Project`
- r/ARG / r/puzzles — `Design`

**Hacker News**
- Show HN framing optional; works as a plain link. Tags are organic — lead the comment with the mesh broadcast-vs-DM mechanic, that's the HN hook.

**Medium / Dev.to**
- `cryptography`, `meshtastic`, `lora`, `iot`, `game-design`, `python`, `networking`, `security`

**Hashtags (X / LinkedIn / Mastodon)**
- `#Meshtastic` `#LoRa` `#cryptography` `#Vigenere` `#meshnetworking` `#gamedesign` `#milsim` `#DevOps` `#IoT`

## Channel-specific angle notes

- **r/cryptography**: downplay airsoft, emphasize *distributed key recovery* as the real difficulty and Vigenère-as-deliberate-choice. They'll respect the "weak cipher + strong key-hiding" reasoning.
- **r/meshtastic**: lead with the hardware + the broadcast/DM/PKC mechanic. This is their home turf — they'll appreciate the config and the `destinationId` lesson.
- **Hacker News**: the title that performs is the *idea*, not the event. "A crypto puzzle where the whole objective compressed into one function argument" is the hook.
- **LinkedIn (career/DevOps angle)**: frame as systems thinking end-to-end — threat model, constraints, real radio stack, post-mortem. This is the portfolio-piece framing.

## Suggested canonical home

Publish on a personal site/blog as canonical, then cross-post to Medium/Dev.to with `rel=canonical`, and link (not full-repost) from Reddit/HN.
