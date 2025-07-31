## MCP DEV DAYs Workshop | notes

## LINKS
- Day 1 event page[https://developer.microsoft.com/en-us/reactor/events/26140/?event_check_in=%20RrzA1n39pMavdaZ6PE4mblJaD9/LpqgOwnj1N7WR%2056TmZ815zLcC2rZMhW8qq2TunjskpPyWumNz690zr8Yg==#msdynttrid=AlLkM2ooUpZQq_ciyf1zamoN3S89vv1r6TrpyVYbzC0]

Workshop Repo[https://github.com/microsoft/mcp-for-beginners/]

Browse MCPs[https://code.visualstudio.com/mcp] for agent mode



## Gen Notes
- mcp.json > check server is started
- user settings > auto approve
- pre-configured prompts; eg. /debug-page
- SDKs?
- turning MCP tools on and off? 



### Day 1 - DevTools ________________________

## ANTHROPIC
- elicitation phase?
- containerizing MCP servers?
- 'mono-repo' for all MCPs
[https://www.anthropic.com/partners/mcp]
[https://github.com/modelcontextprotocol/servers]


## VS CODE MCP use
- playwright?
- microsoft docs, apple docs > in-editor official documentation (through agent/MCP instead of browser)
- sampling

Github MCP; 
- create issues, PRs 
- add feature > 'assign to agent' (look for Assign to Copilot)
- Neon DP?


Community MCP Registry[https://github.com/modelcontextprotocol/registry/tree/main]


NL Web[https://news.microsoft.com/source/features/company-news/introducing-nlweb-bringing-conversational-interfaces-directly-to-the-web/]


## FUTURE of USER INTERACTION
- Having your own 'Jarvis'; NLP + context, multi-modal, immediate response, no config, everywhere (integrated across devices/systems)
- Future is headed towards 'Jarvis clients'

![clients/servers](image.png)
![ressources](image-1.png)

Epic AI[https://www.epicai.pro/]

GibsonAI? > db MCP server


## Visual Studio Productivity
- building custom MCP servers

## ___

** post workshop **
- test create repo > MCP DevDays workshop
- understanding mcp.json file setup/config (1)
- NL Web + EpicAI

1. **MCP.json Setup Brief:**
   - Location: `%APPDATA%\Code\User\mcp.json` (global VS Code config)
   - Install MCP server: `npm install -g @modelcontextprotocol/server-github`
   - Create GitHub Personal Access Token with 'repo' scope
   - Configure server type as "stdio" with npx command
   - Set GITHUB_PERSONAL_ACCESS_TOKEN in env variables
   - Restart VS Code to load configuration
   - Verify server connection through Copilot Chat capabilities 