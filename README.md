# Lab Guide — Git, GitHub & GitHub Actions

**Summit 2026 · NetOps Cloud & DevOps Summit**

---

## Exercise 1 — The Git Loop (in-session)

### What you need

- A browser (Chrome or Firefox)
- A GitHub account with your **@viasat.com email set as primary** (required to join the Inmarsat org)
- The sandbox repo URL — shared by the instructor at the start of the session

### Steps

**1. Open the sandbox repo**

Go to the URL shared by the instructor (e.g. `github.com/Inmarsat/summit-2026-lab`).

**2. Open github.dev**

Press the **`.`** (period) key on your keyboard. The repo opens in a browser-based VS Code editor. No installation needed.

**3. Create a branch**

Click the branch name in the bottom-left corner of the editor (it says `main`).  
Select **"Create new branch"** and name it: `your-name/add-me`  
(e.g. `jane-smith/add-me`)

**4. Find `contributors.md`**

In the file explorer on the left, click `contributors.md` to open it.

**5. Add your name**

Add a new line with your name and team:

```
- Jane Smith (Network Operations)
```

**6. Commit your change**

Click the **Source Control** icon in the left sidebar (looks like a branching line).  
In the text box at the top, write a commit message:

```
feat: add Jane Smith to contributors
```

Click **"Commit & Push"** (or "Commit to Branch").

**7. Open a Pull Request**

GitHub will show a banner: **"Compare & pull request"** — click it.  
Add a one-line description of what you changed.  
Click **"Create pull request"**.

**Done!** The instructor will review and merge your PR live.

---

## Exercise 2 — Your Own Repo (take-home)

### Prerequisites

You need access to the Inmarsat GitHub organisation. Two options:

**Option A — Request access via IT**

1. Open the [IT KB article](https://servicecenter.viasat.com/esc?id=kb_article&table=kb_knowledge&sys_id=0c4f446683233618663dd5547daad33b&recordUrl=%2Fkb_view.do%3Fsys_kb_id%3D0c4f446683233618663dd5547daad33b)
2. Follow the steps to request the AD group that grants access to `github.com/Inmarsat`
3. Once approved, accept the GitHub org invite from your email

**Option B — Use git.viasat.com**

If you already have access to [git.viasat.com](https://git.viasat.com), you can create a repo there directly.

---

### Steps

**1. Create a new repository**

On GitHub: click the **+** in the top-right → **New repository**.  
Choose the Inmarsat org (or your personal account to start).  
Give it a name — something like `my-team-runbooks` or `network-config-backup`.  
Set it to **Private** or **Internal**.  
Tick **"Add a README file"** → click **Create repository**.

**2. Put something in it**

Open it in github.dev (press `.`).  
Add a file — a runbook, a config snippet, a list of useful commands, anything.  
Commit it with a message that explains what it is.

**3. Share it**

Send the repo link to a colleague or your manager.  
Ask them to open a PR with a suggestion or correction — even a typo fix counts.

**4. Optional: add branch protection**

Go to **Settings → Branches → Add rule**.  
Set the branch name to `main`.  
Tick **"Require a pull request before merging"** and **"Require approvals: 1"**.

Now nothing can go into your repo without a review. That's the loop.

---

## Want to go further?

- [GitHub Skills](https://skills.github.com/) — free interactive courses, straight from GitHub
- [Pro Git book](https://git-scm.com/book/en/v2) — free, comprehensive, works as a reference
