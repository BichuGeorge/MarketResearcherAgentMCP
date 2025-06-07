# MarketResearcherAgentMCP

This is a Market Researcher Agent that researches about a product: its strength, weaknes and overall reviews in charts from flipkart or amazon.

1. Use irm to download the script and execute it with iex:

powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

2. Create a boiler plate for the mcp

uv init mcp_server_demo
cd mcp_server_demo

3. Install Dependencies

uv add "mcp[cli]"

4. create a folder called "tools"
 cd tools
5. create __init__.py
6. create mcp_swot.py (To call the server, pass data and get output)
7. uv run mcp
8. npx @modelcontextprotocol/inspector python main.py (To test with inspector tool)
   
![inspector](https://github.com/user-attachments/assets/056eddf0-c0d9-410b-ae63-920a55d6ee51)
