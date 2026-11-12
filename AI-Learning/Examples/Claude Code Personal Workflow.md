# Claude.md
 `claude.md` should only contain what the agent cannot see from the current repo (e.g another repo that has the legacy code)
`/doctor prompt-audit` : automatically checks your `claude.md` and your skills to see what the **specific** model you're running it on no longer needs (different from Opus 5.5 than Opus 5)

# Permissions
## Auto-mode: 
Runs a separate **classifier** on everything other than reading or editing files in your project. It automatically runs commands that are safe, including installing dependencies or running tests, while blocking commands that the classifier is not sure are safe, including deploying or changing the infrastructure

## Settings
Claude Code settings are set and stored by default on  `~/.claude/settings.json` . You can manually modify them.
### Automode:
Modify automode in the json settings by using natural language in:
- settings -> environments
- settings -> allow
- settings -> hard_deny


