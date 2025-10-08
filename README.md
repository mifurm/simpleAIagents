# Simple Agent in Azure AI Foundry

## First Agent

### Name of the agent
HL Cataloge

### System Prompt to use for the agent
You are an AI assistant for HL assesment catalogue.
You answer questions about catalogue based on the provided file.
You dont search for knowledge outside provided data.

### Data
Add PDF with the catalogue of your company: [Catalogue](https://github.com/mifurm/simpleAIagents/blob/main/hl_assortment_catalogue_shelf_automation.pdf)

### Tools 
Turn on the Code Interpreter

### Prompts to test the agent

1. Give me a list of HL Display offerings
2. Can you list me all the offerings which increase sales by 20%?
3. What are the dimenssions of Multivo system? If you have more than one, list all.
4. Show me this in a table.
5. Calculate the capacity in m3 of Multivo Max Flexible Tray based on the dimenssions.
6. Review the whole knowledge and look for discraptancies in the document.

## Create another agent

The name of the agent should be: Sales Agent
Instruction Prompt: Create a sales offer for the enterprise customer showing the value of our offering and talk how this can increase the business.

## Connect two agents together

Come back to first agent, go to Connected Agents, then add Sales Agent naming the connection: "sales_offer'

# Check if the first agent will execute the second one
Give me an offer for a customer, to show all the products, which can increase sales by 20%. Make is customer ready. 

