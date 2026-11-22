# Changelog

## 0.18.0 — 2026-11-22

- Squad33 is now a board your own agent operates through its MCP server; the built-in chat and voice, phone pairing and the tunnel, and the GitHub setup step are gone.
- One coding workflow you can edit, in Admin → Workflow: a map of the ticket lifecycle with each stage's instructions beside it, saved to `~/.squad33/workflows/coding.yaml` and never overwritten by an update.
- A ticket carries its workflow's own context (repository, branch, pull request) instead of fixed fields, and any number of named outputs: links, or local files revealed in Finder.
- A card shows what its agent says it is doing right now, as a live badge, and a running review or merge shows on its card instead of in a banner across the board.
- Idle and overall run limits are settings (Admin → Coding Agents → Run limits), so long work is no longer cut off at a fixed time.
- Codex and Antigravity can work tickets beside Claude Code; OpenCode is gone.
- A running ticket can be paused and resumed, changes can be requested on a ticket in review, and any ticket can be queued whatever its dependencies are doing.
- Moving a ticket to Done merges it; Complete does the same from the card. A failing ticket no longer stops the worker.
- The board has four columns: Backlog, Queue, Review and Done.
- Admin → Plan shows the Free plan: 100 tickets and two agents at once, counted from this update. Upgrading to Pro opens in a later update.
- Onboarding's last step asks whether to send crash reports; nothing is sent until you choose.
- PRDs are retired.

## 0.17.0 — 2026-09-14

- Report a bug from the app, and read what changed in each release, both from the footer.
- A ticket comment can be deleted.
- Onboarding checks Claude Code by asking it, says what is wrong when it is not ready, and re-checks on its own.
- Onboarding shows its five steps as rows, each marked when reached.
- Sign-up and onboarding steps are counted, so we can see where people get stuck.
- A rebase interrupted by a worker restart comes back as a rebase, not a resume.

## 0.16.2 — 2026-09-08

- A voice session holds the Mac out of idle sleep, so a walk no longer ends when the display does.

## 0.16.1 — 2026-09-08

- The mic keep-alive no longer whistles on the phone.

## 0.16.0 — 2026-09-08

- Sign-in gates the app.
- The tunnel channel is TLS.

## 0.15.0 — 2026-09-04

- The pairing step registers on arrival.
