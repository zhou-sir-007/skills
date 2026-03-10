# My Skill

## Description
This skill performs a network search to find relevant information based on the provided query.

## When to Use
Use this skill when you need to search for information on the internet, such as looking up documentation, finding tutorials, or researching specific topics.

## Steps
1. **Initialize the Search Query**
   - The agent will prompt you to provide a search query.
2. **Perform the Search**
   - The agent will use the provided query to search the internet using a predefined search engine or API.
3. **Collect Results**
   - The agent will collect the top results from the search and present them in a structured format.
4. **Provide Summary (Optional)**
   - If configured, the agent can provide a summary of the top results.

## Example Usage
```bash
# Install the network-search skill
npx skills add https://github.com/zhou-sir-007/skills --skill network-search

# Use the skill
npx skills run network-search --query "how to use GitHub Actions"
