<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/banner-dark.svg">
  <img alt="The Holy Earth Foundation: the foundation's golden heart within a breathing halo, framed by a living vine. The banner moves gently; with reduced motion it shows still." src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/banner-light.svg" width="100%">
</picture>

# <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/list-checks.svg" width="32" height="32" alt=""> The Holy Earth Foundation — Procedures, public twin

*How an approved thing is done, step by step, for anyone the foundation chooses to show.*

![Twin](https://img.shields.io/badge/Twin-public-d97706?style=flat-square)
![Allowlist](https://img.shields.io/badge/Allowlist-the_shared_procedures-6b4f1d?style=flat-square)
![Edits](https://img.shields.io/badge/Edits-by_sync_only-b45309?style=flat-square)
![For](https://img.shields.io/badge/For-Visitors-64748b?style=flat-square)

</div>

---

## <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/compass.svg" width="24" height="24" alt=""> What this is

A **proposal** asks for a decision; a **procedure** (a standard operating procedure, SOP) says how an approved thing is
done, step by step, so a person or their helper can do it without the author in the room. The foundation keeps its
procedures in a private repository. This public twin carries **only the procedures an officer has listed**, copied
here by an allowlist sync.

```mermaid
flowchart LR
  H["the foundation's procedures<br/>(private: the house)"] -->|"PUBLIC-ALLOWLIST.txt"| T1{"tripwire 1<br/>keys, credentials,<br/>agent notes"}
  T1 -->|"pass"| T2{"tripwire 2<br/>every file read,<br/>PDFs included"}
  T2 -->|"pass"| W["this twin<br/>(the witness)"]
  T1 -->|"stop"| X["nothing published"]
  T2 -->|"stop"| X
```

## <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/sprout.svg" width="24" height="24" alt=""> What arrives here

On 2026-11-01 the allowlist was given the procedures every organisation in the family shares, with their PDFs and the
icons they draw:

| | Procedure |
|---|---|
| <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/user-plus.svg" width="16" height="16" alt=""> | **SOP-COM-001** New to GitHub: your first hour |
| <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/route.svg" width="16" height="16" alt=""> | **SOP-OPS-001** How a change travels |
| <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/shield-check.svg" width="16" height="16" alt=""> | **SOP-OPS-003** Private houses everything, public lanes witness |
| <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/globe.svg" width="16" height="16" alt=""> | **SOP-IT-001** VPN and DNS resolver stalls |
| <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/door-open.svg" width="16" height="16" alt=""> | **SOP-IT-002** Reading room and helper access |
| <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/lock.svg" width="16" height="16" alt=""> | **SOP-IT-003** Observer dashboards, local by default |
| <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/users-round.svg" width="16" height="16" alt=""> | **SOP-GOV-002** GitHub collaboration |

They arrive, as their markdown and their PDF in the same folders they have in the private repository (`COM/`, `OPS/`,
`IT/`, `GOV/`, `pdf/` and `assets/icons/`), on the **first sync after the sync's deploy key is provisioned**. Until then
this README is the only file here. Members read the full set today in the
[reading room](https://github.com/theholyearthfoundation/reading-room).

## <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/lock.svg" width="24" height="24" alt=""> How it is kept

- **Nobody edits this repository by hand.** A sync in the private repository copies exactly the listed paths, after two
  tripwires: the first stops anything that looks like a credential or an internal note; the second reads **every**
  file, PDFs included, and refuses one no machine could read unless a person attested they read it. *A public lane
  never publishes a file a machine or a person has not read* (SOP-OPS-003).
- This README is the twin's own page; the sync never overwrites it.
- `main` cannot be deleted (a deletion-only ruleset).
- Every procedure is a **draft until its version is tagged** (`v1.0.0` is the first approved set); tagging is an
  officer's action.

## <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/link.svg" width="24" height="24" alt=""> Elsewhere

- <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/globe.svg" width="16" height="16" alt=""> [The foundation →](https://theholyearthfoundation.github.io)
- <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/book-open.svg" width="16" height="16" alt=""> The public reading room (proposals, procedures and decks that are ready for visitors): <https://theholyearthfoundation.github.io/reading-room-public/>
- <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/presentation.svg" width="16" height="16" alt=""> [Welcome to The Holy Earth Foundation](https://github.com/theholyearthfoundation/.github/blob/main/decks/welcome.marp.pdf), the welcome deck
- <img src="https://raw.githubusercontent.com/theholyearthfoundation/.github/main/profile/assets/icons/scroll-text.svg" width="16" height="16" alt=""> How every organisation in the family shapes its procedures: [`drasticstatic/my-template` → `sop-template/`](https://github.com/drasticstatic/my-template/tree/main/sop-template)
