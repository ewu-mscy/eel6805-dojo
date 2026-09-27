# EEL 6805 course dojo (pwn.college)

Private pwn.college dojo for EEL 6805: Advanced Malware Reverse Engineering,
Edward Waters University. All challenges are imported from existing pwn.college
dojos; nothing here needs to be built or hosted.

## What students see

| Module | When | Graded |
|---|---|---|
| Using the Dojo (imported from Start Here) | Module 3 | No, required preparation |
| Your First Program (imported from Computing 101) | Module 3 | No, required preparation |
| Debugging Refresher (imported from Computing 101) | Module 3 | No, required preparation |
| Lab 2: Reverse Engineering with Ghidra (6 challenges) | Module 4 | Yes, Lab 2 |
| Lab 2 Alternates (2 challenges) | Module 4, only if needed | Yes, as substitutes |
| Optional: VM-Based Obfuscation (2 challenges) | Module 6 | No |

## Setup (about 1 hour, once)

1. Use a GitHub account or organization owned by the MSCY program, not a
   personal account, so the dojo survives instructor turnover.
2. Create a repository named `eel6805-dojo` and add this `dojo.yml` and README.
3. In `dojo.yml`, replace `CHANGE-ME-BEFORE-PUBLISHING` with the real password.
   If the repository is public, anyone can read the password. The only effect is
   that an outsider could join and appear on the scoreboard, but a private
   repository is better if pwn.college accepts one for your account.
4. Sign in to pwn.college with the program account, open the Dojos page, and use
   the "Create it here!" link at the bottom of the page. Point it at the repository.
5. Open the new dojo and confirm every module and challenge loads. Start Lab 2's
   first challenge and confirm Ghidra opens from the Desktop.
6. Post the dojo link and password in a Canvas Announcement, not on a public page.

## Updating

Edit `dojo.yml` in GitHub, then update the dojo on pwn.college. If a Lab 2
challenge disappears upstream, swap in an alternate from the Reverse Engineering
module; its ID is in the `program-security-dojo` repository under
`reverse-engineering/module.yml`.

## Source IDs (verified September 27, 2026)

- Start Here: dojo `welcome`, module `welcome`
- Computing 101: dojo `computing-101`, modules `your-first-program`, `debugging-refresher`
- Reverse Engineering: dojo `program-security`, module `reverse-engineering`
  - `level-1-0` Terrible Token (Easy), `level-1-1` Terrible Token (Hard)
  - `level-2-0` Tangled Ticket (Easy), `level-2-1` Tangled Ticket (Hard)
  - `bit-bender` Bit Bender, `substitution-sorcery` Substitution Sorcery
  - `level-6-0` / `level-6-1` Meager Mangler (Easy / Hard), alternates
  - `level-15-0` / `level-15-1` Trust the Yancode (Easy / Hard), optional
