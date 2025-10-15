# BAD_USB — Security Research Notes (Read Me First)

This repository contains text files with titles referencing USB HID automation ("Rubber Ducky") and Windows-focused security scenarios. It is preserved for educational and defensive security research only. It does not endorse misuse and should not be used to perform unauthorized actions.

## Important Disclaimer

- For educational and lawful testing only. You must have explicit, written permission from the system owner before any security testing.
- Do not deploy on networks or devices you do not own or administer with consent.
- The authors and contributors are not responsible for misuse, damages, policy violations, or legal consequences.
- If any content appears to facilitate wrongdoing, treat it as historical reference. Prefer reworking it into defensive guidance or remove it.

## What’s in here

Folder: `BAD_USB/`

- A set of `.txt` files whose names describe potential attack themes, social engineering ideas, or operating system behaviors (e.g., lock jamming, fake updates, password phishing, credential retrieval, etc.).
- Example file names in the folder:
  - `0. Rubber Ducky Setup..txt`
  - `1. Windows 10 Jamming.txt`
  - `2. Windows 10 Defender Hack.txt`
  - `3. Windows 10 WiFi Password Pendrive Version.txt`
  - `4. Windows 10 WiFi Password Hack Email Version.txt`
  - `5. Windows 10 Computer Password Hack And Change.txt`
  - `7. Windows 10  Shut Down.txt`
  - `8. Windows 10 & 11 Voice Hack.txt`
  - `9. Windows 10 Password Phishing Using Webhook.txt`
  - `10. Windows 10 Chrome Browser Saved Password Hack Offline Version.txt`
  - `11. Windows 10 Chrome Browser Saved Password Hack Email Version.txt`
  - `12. Windows 10 Crash Using CMD.txt`
  - `13. How to create Windows Bypass Account Using Ducky.txt`
  - `14. How To Change Windows 10 Wallpaper.txt`
  - `15. Windows 10 Fake Update Prank.txt`
  - `16. Windows 10 Firefox Saved Password Hack Offline Version.txt`
  - `17. Windows 10 Firefox Saved Password Hack Email Version.txt`
  - `18. How To Open Any Link Using Rubber Ducky.txt`
  - `19. Windows 10 Lock Jamming Using USB Ducky.txt`
  - `readme.txt`

Notes:

- File names are preserved for indexing, but you should avoid turning any item into actionable exploitation steps.
- If you keep this repository public, consider adding context to each file that reframes content toward detection, prevention, and awareness.

## Responsible Use Guidelines

- Get written authorization (scope, dates, targets) before any test.
- Prefer demonstrations that are non-destructive and clearly reversible.
- Translate offensive concepts into defensive value:
  - What security control would detect this?
  - How can EDR/SIEM alert on it?
  - Which policies or configurations mitigate it?
  - What user awareness messages reduce risk?
- Keep all demonstrations in an isolated lab environment (e.g., virtual machines with snapshots and no access to production data).

## Safer Lab Setup (High Level)

- Use virtual machines with snapshots to roll back changes.
- Isolate the lab from production networks; use a private, non-routable network.
- Test with non-sensitive, disposable accounts and data only.
- Document expected behaviors and mitigations; avoid storing payloads or secrets in this repository.

## Contributing

- Do not add step-by-step exploitation procedures or payloads that meaningfully facilitate wrongdoing.
- Contributions should prioritize defensive write-ups: detection methods, hardening guides, blue-team playbooks, least-privilege policies, device control, and awareness materials.
- If you find content that crosses the line into harmful instruction, open an issue or replace it with defensive guidance.

## Ethics and Legal

- Many jurisdictions have strict computer misuse laws. Even attempted access without authorization can be illegal.
- Always follow organizational policies, contracts, and legal requirements.

## Reporting Concerns

If you believe any file in this repository provides harmful, actionable instructions, please flag it and replace with content focused on defense, detection, and prevention.

## License and Warranty

This content is provided “as is” without warranty of any kind. Use at your own risk and only for lawful purposes. If you intend to open-source this repository, choose a license that aligns with ethical use and explicitly disclaims misuse.
