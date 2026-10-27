# Development roadmap

[← Project overview](../README.md)

This page describes planned directions, not a list of features already available. Priorities may change as the public beta is tested; there are no committed release dates.

## Available in the current beta

- A six-step workflow: Preparation, Structure, Chapters, Story, Review and Summary.
- A three-act narrative model with sequential chapter progression.
- Narrative graph and entity exploration, manual editing and targeted updates.
- Version history, active versions, comparison, archiving and Trash.
- ChatGPT / Codex and Claude connections through the browser, with optional Windows connectors.
- Project data stored in the browser, project export/import, full archive backups and concept PDF export.
- English and Italian interface, plus an in-app guide.

## Near-term focus: strengthen the beta

- Test connection recovery, account persistence and provider compatibility across more environments.
- Improve loading time and reduce the memory required by browser sign-in runtimes.
- Refine guidance, error messages and the workflow based on user feedback.
- Evaluate practical concurrency limits without moving story archives to a server.

## Narrative evolution

The next architectural goal is to separate two choices:

| Choice | What it defines | Planned examples |
| --- | --- | --- |
| **Dramaturgical structure** | The dramatic functions and progression of the story. | Three Acts, Five Acts, Hero's Journey, Freytag, Kishōtenketsu. |
| **Interactive narrative topology** | How a player moves through events and how choices affect available paths. | Linear, Foldback, Branching; later Hub-and-Spoke and Modular. |

A narrative graph alone does not provide complete alternative playable routes. Supporting them requires changes to chapter planning, context, state and validation throughout the pipeline.

### 1. Make dramaturgical structures configurable

Extract the current three-act assumptions into declarative templates while preserving existing projects. Add Five Acts and Hero's Journey with linear progression first. Adapt narrative elements and gameplay policy to dramatic roles rather than fixed act numbers.

### 2. Introduce a state-aware Foldback workflow

Support decisions that lead to different events before reconnecting at shared narrative points. Preserve consequences at those reconnections: a character's fate, acquired knowledge or an item must remain consistent with the chosen path.

### 3. Support branching paths throughout generation

Keep alternative routes in the chapter plan and use the context relevant to each route during text generation. Prevent events from one branch from being treated as established facts in another.

Use deterministic checks for graph properties such as reachability, valid references and endings, alongside narrative consistency review.

### 4. Explore more advanced structures

Evaluate Hub-and-Spoke and Modular narratives after the simpler topologies are reliable. Cyclic, episodic and emergent structures require further design and are longer-term research directions.

## Principles to preserve

- **Author control:** generated content remains open to review, editing and explicit approval.
- **Local project storage:** stories and version history stay under the user's control in the browser.
- **Browser access:** avoid mandatory installation for the main experience; keep local connectors optional.
- **Compatibility:** evolve schemas and templates without silently changing existing stories.
- **Manageable generation cost:** investigate generating selected paths on demand instead of expanding every possible route at once.

Version history and playable branches will remain separate concepts: one records creative revisions, while the other describes paths within the narrative.

[← Back to the project overview](../README.md)
