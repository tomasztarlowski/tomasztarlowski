# GitHub Promotion Playbook

Short, practical checklist for making `github.com/tomasztarlowski` look more intentional.

## Already built here

- Profile README aligned with the canonical copy from `ivvo.pl`.
- Visual banner for immediate recognition.
- A custom `ivvo` slash-signature wordmark and profile standard in `assets/`.
- Generated public-work section powered by GitHub API.
- Weekly GitHub Action that refreshes public repo data.
- Editable project copy in `data/project-copy.json`.

## Highest-impact next steps

1. Pin the strongest repositories on the GitHub profile:
   `NEWIVVO`, `maccleaner-pro`, `NTFSonMAC`, `WiFi-ESP32--Scanner`, `proteaAI`, and one polished client-safe case study when available.
2. Add concise descriptions and topics to public repos that are currently empty:
   `NEWIVVO`, `WiFi-ESP32--Scanner`, and `proteaAI`.
3. Add a screenshot or short GIF to every important project README.
4. Keep forks visible only when they support your positioning; the profile README intentionally promotes original repos first.
5. Turn one local project into a public case-study repo with a clean README, demo link, screenshots, and architecture notes.
6. Reuse the `ivvo` slash signature consistently in repo social previews, pinned project READMEs, and future ivvo materials.

## Suggested repo descriptions

- `NEWIVVO`: IVVO workspace: strony, aplikacje, UX, integracje i system od briefu do produkcji.
- `WiFi-ESP32--Scanner`: ESP32 Wi-Fi scanner playground for wireless/network experiments.
- `proteaAI`: AI automation prototype space for service workflows and product experiments.

## Maintenance

Run this locally after changing project copy:

```bash
npm run refresh
```

The GitHub Action also runs every Monday morning and can be triggered manually from the Actions tab.
