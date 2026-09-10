<!-- Canonical "Neuronection ecosystem" block — single source of truth for the family.
     Editing home: dev/templates/branding/ECOSYSTEM.md (internal).
     Public canonical (byte-identical copy for humans/public tooling):
       raw.githubusercontent.com/neuronection/.github/main/ECOSYSTEM.md
     Keep both byte-identical. The script injects ONLY the content between the
     NEURONECTION:*:START / :END markers below; comments outside markers are
     never shipped into product READMEs.

     Placeholder contract:
       {{PROJECT}}   replaced with the target repo's display title.
       {{CONTACT}}   replaced with the mailto link line: the project's own
                     contact where one exists (Health Assistant:
                     info@health-assistant.io), always followed by the
                     org-wide info@neuronection.com.

     Synced by the internal dev repo ONLY (dev/scripts/sync_ecosystem.py, run
     from dev/ — the script is never vendored into product repos):
       python3 scripts/sync_ecosystem.py                # all projects
       python3 scripts/sync_ecosystem.py --check        # drift gate
-->

<!-- NEURONECTION:ECOSYSTEM:START -->
---

<div align="center">

### Part of the Neuronection family

**{{PROJECT}}** is one of four connected, open-source (Apache-2.0) AI assistants
for life's big decisions — structured data instead of text dumps, AI that explains
its reasoning, and you in control of your information.

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://neuronection.com/logos/health-light.svg">
        <img src="https://neuronection.com/logos/health.svg" height="34" alt="Health Assistant">
      </picture>
      <br>
      <a href="https://neuronection.com/en/health/"><strong>Health Assistant</strong></a>
      <br><sub>Self-hosted, privacy-first health records — lab results, biomarkers, documents and AI-powered insights into your own data.</sub>
      <br><sub><a href="https://github.com/health-assistant-io/health-assistant">GitHub</a> · <a href="https://health-assistant.io">health-assistant.io</a></sub>
    </td>
    <td width="50%" align="center" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://neuronection.com/logos/career-light.svg">
        <img src="https://neuronection.com/logos/career.svg" height="34" alt="Career Assistant">
      </picture>
      <br>
      <a href="https://neuronection.com/en/career/"><strong>Career Assistant</strong></a>
      <br><sub>A mapped universe of jobs — family tree + relation graph, AI match scoring and university pathways, built for students deciding their future.</sub>
      <br><sub><a href="https://github.com/neuronection/career-assistant">GitHub</a> · <a href="https://github.com/neuronection/career-assistant/tree/main/docs">Docs</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="https://neuronection.com/logos/study.svg" height="34" alt="Study Assistant">
      <br>
      <a href="https://neuronection.com/en/study/"><strong>Study Assistant</strong></a>
      <br><sub>A local-first study workbench, in browser or on desktop — AI-powered course library, handwriting, chat and practice; math-first, subject-agnostic.</sub>
      <br><sub><a href="https://github.com/neuronection/study-assistant">GitHub</a> · <a href="https://github.com/neuronection/study-assistant/tree/main/docs">Docs</a></sub>
    </td>
    <td width="50%" align="center" valign="top">
      <img src="https://neuronection.com/logos/desktop.svg" height="34" alt="Desktop Assistant">
      <br>
      <a href="https://neuronection.com/en/desktop/"><strong>Desktop Assistant</strong></a>
      <br><sub>A system-tray AI launcher for Windows, Linux and macOS — global hotkey, streaming chat, voice input, attachments; local-only history.</sub>
      <br><sub><a href="https://github.com/neuronection/desktop-assistant">GitHub</a> · <a href="https://github.com/neuronection/desktop-assistant/tree/main/docs">Docs</a></sub>
    </td>
  </tr>
</table>

Created and maintained by [Ilias Chatzopoulos](https://github.com/constLiakos)
· [LinkedIn](https://www.linkedin.com/in/ilias-chatzopoulos-aabb22163/)
· {{CONTACT}}

[neuronection.com](https://neuronection.com) — one ecosystem, four guides
· [♥ Support development](https://buymeacoffee.com/neuronection) · star what you use

</div>

<!-- NEURONECTION:ECOSYSTEM:END -->
