# VAULT GOES HERE — placeholder, delete before pushing

**This file is scaffolding. G4 replaces it with the actual vault contents and
deletes this file.** If you are reading this on github.com, something went out
early.

## What G4 drops in, alongside `README.md`

Copy these from the finished `Second Brain Live - Part 4` vault, at the same
names:

```
1-Labs/                      six lab notes plus images/
2-Skills/                    carried unchanged from part 3
3-Acme Corp/                 the organisational brain
4-Acme Marketing/            the departmental brain
5-Parts Unlimited Project/   the project brain
```

`README.md` in this folder already describes exactly that set, so if the
folders that land here do not match the table in it, fix one or the other
before pushing.

## Three things to decide, not to assume

**1. `6-Stream Admin/` does not ship.** It holds the board, the prompter, the
runbook and the demo fallbacks. Part 3's kit shipped skills, the example brain
and the try-it-yourself material and nothing operational, and that is the right
precedent. **Recommendation: leave it out.** If John wants it in, it is his
call, but the prompter reads oddly to an attendee.

**2. `.obsidian/` is optional.** The repo root already carries one, so a
top-level `.obsidian/` will be what opens if someone opens the whole download
in Obsidian. Copying a second one into `part-4/` is harmless but does nothing.
Leaving it out is tidier.

**3. Nothing with a real name in it comes near this folder.** No
`recipients-*.csv`, no HubSpot export, no internal path, no credential. The
three brains are fictional and must stay that way. RULINGS 14.

## The push

**Not this goal's job and not automatic.** The branch is `part-4`, committed
locally, unpushed. G4 pushes to `main` **only on John's word**, after a
fresh-unzip test.

When it is time:

```
cd out/kit/repo
git status                 # expect clean
git checkout main
git merge part-4
git push origin main
```

Then check the folder renders on github.com signed out, and only then say the
URL on air.
