### v0.16.0

date: Jun 8, 2026

- improv: Refreshed landing page design by @0verread
- improv: Updated privacy policy by @hg0-7
- improv: Updated app download link by @0verread
- improv: Small UI improvements throughout the app for a smoother experience by @0verread
- fix: Fixed an issue where past session summaries weren't loading correctly by @0verread
- improv: Context from past sessions is now injected more selectively, keeping responses focused on what you asked by @hg0-7
- improv: Agents now preserve important technical detail in their answers when your question calls for it by @hg0-7

---

### v0.15.1

date: Jun 7, 2026

- feat: When pulling context from other branches, the app now prioritizes your locally tagged branches, then merged and active ones by @hg0-7
- improv: Project and workspace references are now consistent throughout the app by @hg0-7
- arch: Added optional tooling to monitor and improve AI response quality behind the scenes by @hg0-7

---

### v0.15.0

date: Jun 6, 2026

- feat: You can now tag branches across multiple repositories to organize your work by @0verread
- improv: New composer models that spawn agents faster by @0verread
- improv: Agents now better understand Modulus concepts like repos, branches, and sessions by @0verread
- arch: All server requests now require sign-in, keeping your data secure by @0verread
- fix: Creating a new branch no longer accidentally duplicates repository entries by @0verread
- arch: Anonymous usage analytics added to help us improve reliability and performance by @0verread

---

### v0.14.1

date: Jun 5, 2026

- feat: A simple onboarding page to help you get started with the app by @0verread
- fix: Fixed issues in the model provider settings section by @0verread
- feat: Sign-in is now required to use backend services, protecting your account and data by @0verread
- improv: The app is better at finding and returning related past sessions by @0verread

---

### v0.14.0

date: Jun 4, 2026

- improv: Redesigned main sidebar for easier navigation by @0verread
- improv: Redesigned Git sidebar with a cleaner layout by @0verread
- improv: Added an animated splash screen when launching the app by @0verread

---

### v0.13.1

date: Jun 3, 2026

- improv: Your prompts are only enriched with past context when it's actually relevant to what you're asking by @hg0-7
- improv: Better handling of which past conversations get pulled into your current prompt by @hg0-7
- arch: General backend improvements for indexing and augmentation features by @hg0-7

---

### v0.13.0

date: Jun 1, 2026

- feat: Create pull requests directly from the app by @0verread
- feat: Push changes with auto-generated commit messages by @0verread
- feat: Add your own Claude Code API key in settings by @0verread
- feat: Your prompts can now be enriched with context from work on other branches by @0verread
- feat: Comment on code changes and iterate based on your feedback by @0verread
- feat: Delete branches directly from the app by @0verread
- improv: In-app styled dialogs replace native system dialogs for a more consistent look by @0verread
- improv: "Open with Other App" moved to the right sidebar for easier access by @0verread
- arch: You stay signed in between app restarts without having to log in again by @0verread
- arch: Commit messages and pull request details are now generated more securely by @0verread
- arch: Commit message and pull request generation now runs entirely on Modulus infrastructure by @0verread
- arch: Updated how repositories and chat sessions are stored to support upcoming features by @0verread
- feat: Minimalist web dashboard with GitHub sign-in by @0verread
- improv: AI responses sound more natural and stay on topic by @hg0-7

---

### v0.12.6

date: May 30, 2026

- arch: Backend improvements to how session context is fetched and organized by @hg0-7

---

### v0.12.5

date: May 29, 2026

- feat: Deleting a branch now also cleans up its associated chat summaries by @hg0-7

---

### v0.12.4

date: May 27, 2026

- improv: The app is better at deciding when your prompt needs context from past sessions and when it doesn't by @hg0-7

---

### v0.12.3

date: May 26, 2026

- improv: Improved how the app finds useful context from your past conversations and other branches by @hg0-7

---

### v0.12.2

date: May 24, 2026

- improv: Casual or non-coding messages no longer trigger unnecessary context lookups by @hg0-7

---

### v0.12.1

date: May 23, 2026

- feat: Agents can now pull relevant context from your work across different repositories and branches by @hg0-7

---

### v0.12.0

date: May 20, 2026

- feat: Codex agent support by @0verread
- feat: Plan mode enabled in Claude Code by @0verread
- feat: Open a terminal as a session tab by @0verread
- feat: Token usage display for Claude Code sessions by @0verread
- arch: Support for working across multiple workspaces in a single app install by @0verread
- fix: Fixed a crash that could occur when switching between chat sessions by @0verread
- fix: Fixed a startup crash related to app permissions on macOS by @0verread

---

### v0.11.1

date: May 19, 2026

- fix: Fixed an error that occurred when sending messages with no text by @0verread
- improv: Session summaries are now correctly scoped to the workspace you're working in by @hg0-7

---

### v0.11.0

date: May 15, 2026

- feat: Chat threads now get automatic summaries so agents remember what you discussed by @0verread
- feat: Agents can use summaries from other chats on the same branch to inform your current prompt by @0verread
- improv: Settings dialog opens as a separate window for easier access by @0verread
- improv: Your prompts on the same branch can be enriched with context from earlier conversations by @0verread
- arch: Claude Code now runs more reliably as an integrated part of the app by @0verread
- fix: Fixed agent switching when uninstalling agents by @0verread

---

### v0.10.5

date: May 14, 2026

- improv: Short or casual messages no longer generate unnecessary session summaries by @hg0-7

---

### v0.10.4

date: May 13, 2026

- feat: Past session summaries are now searchable, so the app can find relevant context from older conversations by @hg0-7

---

### v0.10.3

date: May 11, 2026

- arch: Internal quality checks added to improve summary and response accuracy over time by @hg0-7

---

### v0.10.2

date: May 10, 2026

- feat: When you ask a new question, the app surfaces relevant context from your past session summaries by @hg0-7

---

### v0.10.1

date: May 7, 2026

- feat: Chat sessions are now automatically summarized in the background, laying the groundwork for cross-session memory by @hg0-7

---

### v0.10.0

date: May 5, 2026

- feat: Users should be able to send submit feedback to us from the app by @0verread
- improv: Default full screen mode for app @0verread
- improv: image support for claude code by @0verread

---

### v0.9.2

date: May 2, 2026

- fix: app crashed (v0.9.1) for mismatch of libssl version  @0verread

---

### v0.9.1

date: Apr 23, 2026

- improv: User prompt area improvements @0verread
- improv: Redesign git diff panel @0verread

---

### v0.9.0

date: Apr 10, 2026

- feat: enhanced prompt should be visible to users' @0verread
- feat: Allow users to open working directory in external applications @0verread
- feat: Cross-chat context (beta) @hg0-7
- improv: Support of localDB and persistent of chat history @0verread
- improv: Sidebar Redesign for better UX @0verread
- improv: new Diff view @0verread

---

### v0.8.2

date: Mar 9, 2026

- fix: Show tools and messages for Claude code ( like Codex ) @0verread 
- improv: new install window ( and install script with create-dmg npm pkg) @0verread 

---

### v0.8.1

date: Mar 5, 2026

- feat: Augment API to every message @hg0-7
- feat: Local Indexing v1 @hg0-7
- improv: Allow users to select Agent models @0verread
- fix: Indexing fix - calling upload api for files to be indexed @hg0-7
- fix: claude code code gen and UI changes by @0verread
- improv: Use GitHub username as workspace_id for Colorado upload and augment APIs @hg0-7
- improv: Context augmentation of user prompt by @0verread
- improv: default window size is increased @0verread

---

### v0.1.0 - v0.8.0

date: Feb 16, 2026

- feat: We just shipped, tested and fixed whatever is broken. There was no time for maintaining changelog. @hg0-7 @0verread
