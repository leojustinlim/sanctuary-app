# Sanctuary

**An interactive plant-care and reflection storytelling proof of concept**

[Try the live prototype](https://leojustinlim.github.io/sanctuary-app/) · [View the source code](https://github.com/leojustinlim/sanctuary-app)

Sanctuary is an independently conceived, AI-assisted digital prototype exploring how character-led storytelling and small caregiving decisions can invite personal reflection. Users accompany three plants through their stories and gradually make a cottage their own. It is a creative wellbeing experience, **not a clinical mental-health intervention or a substitute for professional support**.

## Experience

- **Three plant journeys:** each plant has 30 narrative events with three caregiving choices per event, giving 90 events and 270 written choice responses in total.
- **Daily pacing by default:** complete up to one new event per plant per local day. A separate **Demo Mode**, available under **Settings & privacy**, removes the wait for exploring the prototype.
- **Optional reflection:** write private reflections while progressing through stories, and revisit completed moments in the cottage journal.
- **Collectible keepsakes:** unlock keepsakes along the way, view their stories, and drag them into position inside the cottage. Place and store items through the inventory.
- **Personal touches:** pin and arrange notes inside the cottage.
- **Local progress:** adopted plants, progress, choices, placements and reflections are saved in the browser, with JSON export and import for backups.

## How to explore

1. Open the [live prototype](https://leojustinlim.github.io/sanctuary-app/) and select **Adopt**.
2. Choose a plant, read its story, then select one of the caregiving responses.
3. Finish the event and return on another day for the next chapter, or turn on **Demo Mode** in **Settings & privacy** if you want to explore the full interaction immediately.
4. Open **The Cottage** to view your journal, arrange keepsakes, and pin notes.

No account is required. Progress is local to the browser and device; it does not automatically sync between devices.

## Technology

- **HTML, CSS and vanilla JavaScript** for the application and responsive interface.
- **SVG** illustrations for character and story scenes.
- **Browser localStorage** for progress and reflections.
- **JSON** import/export for user-managed backups.
- **GitHub Pages** for hosting.

The project is a client-side proof of concept rather than a production-ready hosted service.

## Project goals and approach

The goal is to test a gentle alternative to conventional journaling prompts: a narrative in which decisions about how to care for a plant make space for users to reflect on care, uncertainty, patience, and progress. The prototype combines structured story content, interactive choices, a consistent visual language, and a personalisable cottage. Its design has been revised iteratively to improve typography, spacing, illustration consistency, pacing, and navigation.

**Development approach:** independently conceived and refined with AI assistance for implementation and content iterations. The prototype does not claim clinical effectiveness or validated wellbeing outcomes.

## Screenshots

The [live prototype](https://leojustinlim.github.io/sanctuary-app/) is the most current visual reference. Representative screenshots of the landing page, a story event, and the cottage can be added here following browser-based visual QA.

## Privacy and limitations

- Story progress, notes, choices, and reflections are stored locally in the browser. Clearing browser storage may remove them; exported JSON backups can help preserve them.
- This project has not undergone formal user research, clinical validation, or a comprehensive accessibility audit.
- Mobile and cross-browser testing, including Safari touch interactions, should be completed before representing it as production-ready.
- There is no user account, cloud synchronization, or hosted backend.

## Author

**Proof of concept developed by Justin Lim.**
