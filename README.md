# Cal.diy scheduling — TrillionAI source-code research

Independent research copy of the open-source [calcom/cal.diy](https://github.com/calcom/cal.diy) project, for studying booking, scheduling, availability, calendar integrations and notification workflows in TrillionAI Marketing and Manager.

## Important: Cal.com and Cal.diy are different in 2026

In April 2026 Cal.com moved its commercial production code into a private repository. Public `calcom/cal.com` links redirect to **Cal.diy**, which is the independent open-source community edition. Its own README says it is intended primarily for self-hosting/personal use; **this snapshot is not the proprietary commercial Cal.com product implementation and does not prove Cal.diy generates revenue**.

- Commercial product: [cal.com](https://cal.com)
- Source research reference: [calcom/cal.diy](https://github.com/calcom/cal.diy)
- Pinned upstream commit: `ae027bb70e694e2d2c44569f398d6cbcee0389b1`
- Pinned upstream Git tree: `a97f0c5a05befbf6c6ee37c788448c05628f27dc`
- Dedicated source branch: [`cal-diy-upstream-snapshot`](https://github.com/Anselm04/CalCom-Source-Code-Reference/tree/cal-diy-upstream-snapshot/upstream)
- Original source stored under `upstream/`
- [Import and Git-tree verification workflow](https://github.com/Anselm04/CalCom-Source-Code-Reference/actions/workflows/import-cal-diy-source.yml)

**GitHub Actions verified the upload.** This security-filtered snapshot retains **7,711 of 7,712** upstream tracked files. The token-bearing `apps/web/calendso.yaml` was omitted without bypassing GitHub push protection. The final retained Git tree is `917c9be2f9a11a6a0b3d7888ff38fcc76e5a8471`. [Successful import verification](https://github.com/Anselm04/CalCom-Source-Code-Reference/actions/runs/43540961871). This is the tracked source at one commit, not the full commit history, external submodule payloads, independently retrieved LFS objects, or any private commercial service.

## Copyright and licensing

Cal.diy's upstream root `LICENSE` states MIT (Copyright Cal.com, Inc.). All Git-tracked copyright, licence, and original attribution files are preserved. Check file-specific and third-party licences before reuse.

## Engineering separation

This is an engineering research repository, not runnable TrillionAI production code. Do not merge the snapshot into commercial TrillionAI repositories or execute imported applications as part of source archival. Design and test original Flutter/Node.js implementations as required for our three-product launch. No paid infrastructure or cloud services activated.
