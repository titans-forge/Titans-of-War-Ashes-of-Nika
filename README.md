# Titans of Constantinople: Ashes of Nika

[Play on itch.io](https://titans-forge.itch.io/titans-of-war-ashes-of-nika) ·
[Forge source](https://github.com/titans-forge/Titans-of-War-Ashes-of-Nika) ·
[Report an issue](https://github.com/titans-forge/Titans-of-War-Ashes-of-Nika/issues) ·
[Game collection](https://github.com/titans-forge/educational-games)

This is the Ashes of Nika entry in the Titans of War collection. The existing
repository moved from JCapone83 to Titans Forge on September 30, 2026, retaining
its history and licensing checkpoints. Historical owner names in those records
remain intentional; earlier MIT grants and separate media rights are preserved.
The source branch is not certified to match the current itch.io build.

A deterministic historical city-building strategy game about rebuilding Constantinople after the Nika revolt. The player governs twelve seasons from winter 532 through autumn 534, balancing urban recovery against factional politics, frontier security, and the opening of Justinian's western wars.

The game does not require an account, server, or AI model. Campaign state is stored only in the browser.

## Play

```bash
git clone https://github.com/titans-forge/Titans-of-War-Ashes-of-Nika.git
cd Titans-of-War-Ashes-of-Nika
npm install
npm run dev
```

Open the local URL printed by Vite. For a production build:

```bash
npm run build
npm run preview
```

## Command Model

- Choose one of six damaged districts on the reconstruction map.
- Commission clearance, housing, water, food, workshop, watch, and fire-control projects.
- Match projects to district strengths for additional effects: harbor granaries, cistern works near surviving reservoirs, artisan workshops among the organized trades, and other site-specific advantages.
- Reassign a fixed pool of field forces between the East, Africa, the Balkans, and the capital reserve.
- Resolve seven imperial councils grounded in the political and material problems of 532-534.
- Read the next seasonal pressure before committing orders, then review a deterministic after-action report.
- Finish with separate grades for urban recovery, political order, imperial strategy, fiscal reserve, and legitimacy.
- Open the optional walkthrough or public-works context from the header at any time.
- Copy or download the final imperial chronicle as a local Markdown record.

This is a game model, not a claim that the Byzantine administration used modern numerical meters. Resources and scores make historical constraints legible; decision notes identify the period evidence behind the situations.

## Historical Scope

The first release concentrates on the immediate reconstruction problem after Nika: factional grievance, burned districts, public employment, bread and water, the rebuilding of Hagia Sophia, the Persian settlement, the African expedition, reconstruction contracts, and the revised Code of 534. The principal primary-source starting points are Procopius, John Malalas, John Lydus, the *Chronicon Paschale*, Paul the Silentiary, and the *Codex Justinianus*.

## Verification

```bash
npm test
npm run balance
npm run build
```

## License

Current project policy: [Forge Game Hosting License 1.0](LICENSE), with the
release boundary recorded in [LICENSING.md](LICENSING.md) and
[LICENSING_CHECKPOINT.json](LICENSING_CHECKPOINT.json).

For newly covered material, companies with gross annual revenue **over
US$1,000,000** need a separate written licence to publicly host their own playable
copy. Ordinary playing and private internal/classroom use do not require one.
See the full terms for platform embeds, revenue calculation and exceptions.

**Earlier MIT permissions remain available.** The original notice is preserved in
[LICENSE-LEGACY-MIT.txt](LICENSE-LEGACY-MIT.txt). Previously MIT-licensed code,
documentation and assets keep those grants, including hosting rights for the same
material. Existing media and third-party rights/credits remain unchanged.
This policy update does not rewrite old releases or make identical MIT material
exclusively Forge-licensed. Future covered game changes need a distinct release
boundary. [Commercial inquiries](https://titans-forge.itch.io/).
