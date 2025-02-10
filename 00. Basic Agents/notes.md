CrewAI Agents Tool

Design Pattern: Quality Assurance
- Agent 1 -- Do Task
- Agent 2 -- Review Task. Review Task can delegate tasks

Tools:
- WebsiteSearchTool. makes use of RAG of searchtool
Different Ways to Give Agents Tools
Agent Level: The Agent can use the Tool(s) on any Task it performs.
Task Level: The Agent will only use the Tool(s) when performing that specific Task.
Note: Task Tools override the Agent Tools.

Elements of good tools. Versatile, Fault tolerant, Caching

Tools -- search the internet, scrap a website, connect to a database, call an api, send notifications
Tools are a cornerstone


Task Customisation Options:
- Clear description of task
- Set a clear and concise expectation
- Set context
- Set a callback
- Override Agent tools with specific task tools
- Force human input before end of task
- Execute asynchronously
- Output as PyDantic
- Output as JSON
- Output as File
- Run in parallel

- We organise the tasks and not the agents. For example, tasks can run in parallel and in 