# Discovery: Get gastown repo, understand it, and set it up

Started: 2026-01-03 13:21

## Questions Asked

### Iteration 1 - Core Intent
1. What's your primary goal? (Use/Contribute/Study/Other)
2. Experience level with prerequisites? (Power user/Partial/Fresh/Not sure)
3. What environment? (Personal/Work/Server/Container)

### Iteration 2 - Usage Context
4. What project(s) to orchestrate? (This repo/Specific/Multiple/Exploring)
5. How many concurrent agents? (Light 2-5/Medium 5-15/Heavy 15-30/Not sure)
6. Where to install gastown? (~/gt/Custom/Current dir/Not sure)

### Iteration 3 - Multi-Project Setup
7. What types of projects? (Web apps/CLI-Libraries/Mixed/Monorepo)
8. Existing or new projects? (Existing/New/Both/Not decided)
9. Who manages repo cloning? (Gastown/Manual/Mixed/Not sure)

### Iteration 4 - Workflow & Knowledge
10. Familiar with gastown concepts? (Yes/Somewhat/No/Just basics)
11. How to interact with agents? (Full tmux/Dashboard/Hands-off/Not sure)
12. What tasks to delegate? (Features/Bugs/Refactoring/All)

### Iteration 5 - Learning & First Steps
13. Learning preference? (Docs/Hands-on/Guided tutorial/Video)
14. First project in mind? (Specific repo/New idea/No preference/Toy project)
15. Biggest concern? (Cost/Complexity/Safety/None)

### Iteration 6 - First Project & Subscription
16. First repo type? (Public GitHub/Private GitHub/Private other/Local)
17. Project size? (Small <10k/Medium 10-50k/Large 50k+/Not sure)
18. Claude Code authentication? (Max sub/API key/Not set up/Not sure)

### Iteration 7 - Workflow Expectations
19. Team size? (Solo/Small 2-5/Larger 6+/Open source)
20. Tech stack? (JS/TS/Python/Go/Other)
21. CI/CD and tests? (Both/CI only/Tests only/Neither)

### Iteration 8 - Expectations & Edge Cases
22. First task for agents? (Specific feature/Bugs/Cleanup/Explore first)
23. How to review agent work? (PR-based/Branch inspect/Trust+verify/Not sure)
24. Agent mistake recovery? (Git revert/Need guidance/Want safeguards/Low stakes)

### Iteration 9 - Setup Preferences
25. Keep gastown source here? (Yes for learning/No just binaries/Both/Not sure)
26. Shell preference? (zsh/bash/Doesn't matter/Other)
27. After setup next step? (Add project/Demo first/Read concepts/Quick tour)

### Iteration 10 - Demo & Onboarding
28. Demo project type? (Todo app/API server/Full-stack/Built-in examples)
29. Time for setup? (15-30min/1-2hrs/No rush/Install now explore later)
30. GitHub CLI installed? (Yes/No/Not sure/Use SSH)

### Iteration 11 - GitHub Access
31. Current private repo access? (HTTPS token/IDE auth/Not sure/Not cloned yet)
32. Preferred auth setup? (gh CLI/SSH keys/Both/Guide me)
33. Include GitHub setup? (Yes/No/Later/Already have a way)

### Iteration 12 - Configuration & Preferences
34. Auto-start gastown? (Yes in .zshrc/No manual/Not sure/Conditional)
35. Setup verbosity? (Explain all/Key points/Just do it/Interactive)
36. Cheat sheet after setup? (Written file/Verbal/No/Both)

### Iteration 13 - Edge Cases & Finalization
37. If installation fails? (Debug together/Handle it/Stop report/Try alternatives)
38. Existing tmux config? (Customized/Default/Not sure/Heavy)
39. Any other concerns? (No/Yes/Minor things/Review plan first)

## Answers Received

### Iteration 1
1. **Use gastown** - Want to run it to orchestrate AI agents on projects
2. **Not sure** - Need help checking what prerequisites are installed
3. **Personal dev machine** - Full control, can install anything

### Iteration 2
4. **Multiple projects** - Want to manage several repos
5. **Light (2-5 agents)** - Testing the waters first
6. **~/gt** - Use default recommended location

### Iteration 3
7. **Web apps** - Frontend/backend, APIs, full-stack projects
8. **Both** - Mix of existing and new projects
9. **Gastown manages** - Use `gt rig add` for project management

### Iteration 4
10. **No** - New to gastown concepts (Mayor, Polecats, Beads, etc.)
11. **Dashboard only** - Monitor progress without diving into tmux sessions
12. **All of the above** - Features, bugs, refactoring - full spectrum

### Iteration 5
13. **Hands-on** - Learn by doing, dive right in
14. **Specific repo** - Has a particular project in mind to start with
15. **Complexity & Cost** - Worried about both; wants to use Max subscription NOT API keys

### Iteration 6
16. **Private GitHub repo** - Has access, hosted on GitHub
17. **Medium** - 10k-50k lines, moderate complexity
18. **Already using Max** - Claude Code CLI authenticated with Max subscription

### Iteration 7
19. **Solo developer** - Working alone on the project
20. **JavaScript/TypeScript** - Node, React, Vue, etc.
21. **Uncertain** - Thinks there's a test script, needs verification

### Iteration 8
22. **Explore first** - Want to understand capabilities before specific tasks
23. **Trust but verify** - Let agents merge, review after
24. **Git revert** - Comfortable reverting if agents make mistakes

### Iteration 9
25. **Yes, keep source** - Keep gastown source at /home/martin/dev/gastown for learning
26. **zsh** - Default shell
27. **Demo first** - Practice with a test project before real repo

### Iteration 10
28. **Simple todo app** - Classic, easy to understand demo
29. **No rush** - Take whatever time needed
30. **Not sure** → CHECKED: gh NOT installed, SSH NOT configured

### Iteration 11
31. **HTTPS with token** - Currently using personal access token
32. **GitHub CLI (gh)** - Preferred, modern, recommended by gastown
33. **Yes, include it** - Set up gh CLI as part of this setup

### Iteration 12
34. **No** - Start gastown manually, don't auto-start
35. **Key points only** - Highlight important parts
36. **Written file** - Save a command reference/cheat sheet

### Iteration 13
37. **You handle it** - Just make it work, handle issues autonomously
38. **Not sure** → CHECKED: No .tmux.conf found (clean slate)
39. **No, covered everything** - Ready to proceed

## Emerging Requirements

- Goal: Production USE of gastown for AI agent orchestration
- Environment: Personal dev machine with full install permissions
- Prerequisites: ALL MET (Go 1.25.5, tmux 3.6a, Git 2.52.0, Claude Code 2.0.76)
- Scope: Multi-project orchestration for web apps (frontend/backend/APIs)
- Scale: Starting light (2-5 agents), likely to scale later
- Install location: ~/gt (default)
- Project management: Gastown-managed via `gt rig add`
- Project types: Mix of existing repos and new projects
- Experience: NEW to gastown - needs concept introduction
- Interaction style: Dashboard-focused (less tmux diving)
- Task types: Full dev spectrum (features, bugs, refactoring)
- Learning style: Hands-on, learn by doing
- First project: Has a specific repo ready to use
- Concerns: Complexity + Cost
- CRITICAL: Use Claude Max subscription, NOT API keys
- First repo: Private GitHub, medium size (10-50k lines)
- Auth status: Claude Code CLI already authenticated with Max subscription ✓
- Team: Solo developer
- Tech stack: JavaScript/TypeScript (web apps)
- Testing: Uncertain - has test script, needs verification
- First task: Exploration mode - understand capabilities first
- Review style: Trust but verify (autonomous agents, post-review)
- Git skills: Comfortable with reverts - can recover from mistakes
- Source code: Keep in /home/martin/dev/gastown for learning/reference
- Shell: zsh
- Onboarding: Demo project first (simple todo app), then real repo
- Time: No rush, thorough setup
- GitHub access: NEEDS SETUP (no gh CLI, no SSH keys configured)
  - Currently uses: HTTPS with personal access token
  - Want to set up: GitHub CLI (gh) - include in this setup
  - Required for private repo access later
- Auto-start: NO - manual start preferred
- Verbosity: Key points only during setup
- Deliverable: Written cheat sheet file after setup
- Error handling: Handle issues autonomously
- Tmux config: Clean slate (no existing config)

## Final Summary

### User Profile
- Solo JS/TS web developer on personal Linux machine
- New to gastown, comfortable with git
- Has Claude Code CLI with Max subscription
- Prefers hands-on learning, dashboard monitoring
- Willing to let agents work autonomously with post-review

### Setup Plan
1. Clone gastown source to /home/martin/dev/gastown (for reference)
2. Install gh CLI and authenticate
3. Install gastown binaries (gt, bd) to ~/gt
4. Create simple todo app demo project
5. Walk through basic gastown workflow
6. Save command cheat sheet

### Prerequisites Status
- ✅ Go 1.25.5
- ✅ tmux 3.6a  
- ✅ Git 2.52.0
- ✅ Claude Code 2.0.76 (Max subscription)
- ❌ GitHub CLI → INSTALL
- ✅ No tmux config conflicts

### Key Preferences
- Multi-project use case (web apps)
- Start with 2-5 agents (light)
- Demo first, then private repo
- Key points communication style
- Written cheat sheet deliverable

---

## Discovery Status: COMPLETE
Confirmed ready to proceed: 2026-01-03 13:30
