# Getting started with StoryGEN AI

[← Project overview](../README.md) · **[Open StoryGEN AI](https://storygenai.federicomaglione.com)**

## 1. Open your workspace

Use a recent desktop version of Chrome or Edge. On your first visit, StoryGEN prepares its local workspace. Projects are saved in this browser profile, on this website address.

The interface starts in English. You can switch between English and Italian using **Interface language** in the sidebar. This changes the interface language; describe the desired language of your story in your creative brief.

## 2. Choose an AI connection, or explore the Demo

Select **Connect AI** in the sidebar. Choose ChatGPT / Codex or Claude, then select a connection mode:

- **In the browser:** complete the provider's sign-in flow inside StoryGEN, without installing a component. The first connection downloads additional runtime components; later connections can reuse the browser cache.
- **Local component:** download and run the corresponding Windows connector, then follow the connection instructions. This is an optional alternative to browser sign-in.

Your provider account must support the selected model and have available quota. Claude subscription access requires an eligible plan. A free Claude account alone does not provide that access.

When accounts are connected, **Switch agent** lets you choose which one to use while retaining the other sign-ins. Signing out removes the selected connection.

Without a connected AI account, you can create a project in **Demo mode**. Its yellow label identifies static example content. Changing the prompt does not make the Demo generate a personalised story.

![AI connection choices](../assets/screenshots/connect-ai.png)

## 3. Create a project

Choose **New project** or **Create a new story**, and give the project a name. Describe your premise and creative direction in the preparation workspace.

A useful brief includes:

- The protagonist and what they want.
- The setting, genre and tone.
- The central problem or difficult choice.
- The desired story language and any creative constraints.

For example:

> A cartographer returns to a coastal city where maps change every night. She must decide whether to expose the guild protecting the city or preserve the lie that keeps her family safe. Write in English, with a mysterious tone and meaningful moral choices.

This is an example prompt, not a promise of a particular generated result.

## 4. Work through the six steps

| Step | Suggested approach |
| --- | --- |
| **Preparation** | Establish the premise and creative direction. Generate, inspect and approve the preparation before moving on. |
| **Structure** | Review the world, characters and narrative connections. Explore the graph and entity views; edit or regenerate what needs work. |
| **Chapters** | Check how the approved structure becomes a chapter plan, including encounters and gameplay requirements. |
| **Story** | Develop the narrative from the approved plan. Review the text and use manual edits or targeted updates where needed. |
| **Review** | Inspect continuity and consistency findings. Decide which proposed improvements belong in your story. |
| **Summary** | Gather the key elements into a concise overview and export a concept PDF when ready. |

Later steps use their approved source versions. Changing an earlier result can affect dependent work; inspect the application's notices before continuing.

## 5. Adjust the model settings

Open the phase settings to inspect the selected model, version and reasoning options available for your connection. Settings save automatically; there is no separate **Save Configuration** action.

Changing a model chooses how future requests run. It does not rewrite previously generated text. Provider quotas and model availability can change independently of StoryGEN; quota information is shown when the connection can retrieve it.

## 6. Manage versions

Open **Version history** for the current step.

- **Open** previews a version. It does not make it active.
- The **active version**, marked **✓**, is the one used as a source for subsequent work.
- Activating an earlier version can affect which associated versions are compatible with later steps. Review the activation information before confirming.
- Protect versions you want to retain, or archive them to reduce clutter without deleting them.
- Before moving versions to **Trash**, inspect the preview: dependent versions from other steps may be included.

Permanent deletion from Trash cannot be undone. Export a backup first if you may want to recover that work later.

## 7. Export and back up your work

The sidebar contains two kinds of transfer tools:

| Tool | Use it for |
| --- | --- |
| **Export / Import** | Transfer selected stories between browsers or devices. |
| **Data management** | Export or restore the complete local archive and request persistent browser storage. |

A full archive restore replaces the archive currently in that browser. Review the confirmation and export the existing archive first if you want to retain it.

Story exports do not include your AI sign-ins. Connect your provider account again when using a different browser, profile or device.

## Requirements and current limits

- **Browser:** a recent desktop Chrome or Edge is the recommended starting point for browser AI connections. Compatibility across other browsers and devices is not yet established.
- **Memory and download:** the main workspace and provider sign-in runtimes have different resource requirements. Browser sign-in loads extra components and can use substantial memory, especially for Claude. First sign-in may be slow on modest hardware.
- **Network:** AI generation requires a working connection to the chosen provider. Cached application components do not make AI generation work offline.
- **Sessions:** StoryGEN renews connections where supported. Provider expiry, revocation, prolonged device suspension or network failures may still require reconnecting.
- **Narrative scope:** the beta follows a three-act structure with sequential chapters. Complete alternative playable routes and additional dramaturgical templates remain future work.
- **Availability:** the public beta has limited hosting capacity. A connection error can be temporary; repeated sign-in attempts may also trigger provider rate limits.
- **Storage:** clearing site data, changing browser profiles or changing the website address creates or exposes a different local workspace. Keep exported backups.

## If something goes wrong

1. Check the selected agent and its connection status.
2. Check whether your provider account has quota and access to the selected model.
3. Follow the error shown by StoryGEN. If the provider reports a rate limit, wait rather than repeatedly retrying.
4. Export a backup before clearing site data as a troubleshooting step.
5. Report reproducible issues with the browser, connection mode, narrative step and error message. Do not include tokens, passwords or private story text.

[← Back to the project overview](../README.md)
