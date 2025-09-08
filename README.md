# API Connect for GraphQL and MCP

Prereq: VS Code

This is to show what API Connect for GraphQL offers to enable Agents 

Each trial instance offers a default endpoint like
https://stepzen-chester.us-east-a.ibm.stepzen.net/examples/starwars/graphql 

The same endpoint can also be reached on
https://stepzen-chester.us-east-a.ibm.stepzen.net/examples/starwars/mcp

> [!IMPORTANT]
> The MCP Endpoint is created by default by API Connect for GraphQL

The sample leverages a capability within VS Code to deal with [MCP Servers](https://code.visualstudio.com/docs/copilot/customization/mcp-servers)

<br><br>
## Steps to use MCP in APIC for GraphQL
### Prepare
<br>
1. create an empty folder to work in and open it in VS Code
<br><br>
2. type `>` or F1 to get the commands and look for MCP: Add Server<br>
<img width="889" height="129" alt="image" src="https://github.com/user-attachments/assets/6be916e4-0eda-404f-a3c3-cbbd629e5909" /><br>
<br>
3. Select **HTTP (HTTP or Server-Sent-Events)**<br>
   <img width="714" height="201" alt="image" src="https://github.com/user-attachments/assets/0f7a0907-4465-4d16-bac6-399562144a58" /><br>
<br>
4. Enter the MCP Endpoint:<br>
   https://stepzen-chester.us-east-a.ibm.stepzen.net/examples/starwars/mcp<br>
   and just hit enter for the subsequent values (you might see an error message in VS Code)<br>
<br><br>

### Use the MCP Server
<br>
5. If not already visible, in VS Code go to View->Chat<br>
<img width="205" height="420" alt="image" src="https://github.com/user-attachments/assets/40ff61dc-59ae-4315-82ce-38d451f146ff" />

<br><br>
6. Add the MCP Server as context (search for mcp.json) <br>
   <img width="270" height="113" alt="image" src="https://github.com/user-attachments/assets/1e036a46-973a-476d-b167-58dd32f264cc" /><br>
<br>
7. **Ask a question** like "In which episodes does R2D2 appear?"<br>
The output indicating the MCP-Server has being used, will look like this<br>
<img width="273" height="361" alt="image" src="https://github.com/user-attachments/assets/21733fe2-9b76-47cd-9d84-c66514fef5b6" /><br>
Expand the area in the rectangle to see the details on query and response.
