project
	.claude
		agents
			playwright-automation-agent.md
			playwright-test-generator.md
			playwright-test-healer.md
			playwright-test-planner.md
			qa-analyst-agent.md
		commands
			design-tests.md
			generate-playwright-tests.md
		skills
			xxx-qa-knowledge.md
			playwright-automation-standards.md


## Claude Code Tutorial - Lesson 1
https://www.youtube.com/watch?v=pesfXsYuvto
Notes:

## Para Banks Git Repo:
# https://github.com/parasoft/parabank
## Para Banks URL:
# https://parabank.parasoft.com/parabank/index.htm

## Credentials:
# tententwotwenty
# abcd1234

## Terminal run commands
claude mcp add --scope project playwright npx @playwright/mcp@latest

## if claude cli is not installed, use the terminal command or claude extn in VS code to install the cli.
# macOS, linux, wsl
# terminal: curl -fsSL https://claude.ai/install.sh | bash
# windows
# powershell: irm https://claude.ai/install.ps1 | iex
# cmd: curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd && del install.cmd
# vs code extn: can you install claude cli in this project

npx playwright init-agents --loop=claude

## Install python, node, npm.
## Create python venv

python3 -m venv ./venv 

## Activate venv

source .venv/bin/activate

## Create requirements.txt

pip3 freeze > requirements.txt


## Chat window prompts

use the browser to:
1. Navigate to https://parabank.parasoft.com/parabank/index.htm
2. Login with username: tententwenty, password: n5$ajS$6)]Y],aK
3. Navigate to Transfer Funds page
4. Describe the full DOM structure of the Transfer Fund form
