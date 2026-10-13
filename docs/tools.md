# Tool reference

Read-only tools never change anything. Tools marked **changes data** are labelled so your client can ask before running them.

| Tool | What it does | Behaviour |
| --- | --- | --- |
| `list_calls` | List calls newest first, with filters and paging. | read-only |
| `get_call_details` | Outcome, timing, agent and structured data for one call. | read-only |
| `get_call_transcript` | The conversation of one call, turn by turn. | read-only |
| `get_call_analytics` | Call volume, talk time and inbound/outbound split over a period. | read-only |
| `list_agents` | List your AI voice agents and whether each is live. | read-only |
| `get_agent` | One agent's editable configuration and any unpublished draft. | read-only |
| `list_voices` | The voice catalogue, filterable by gender, accent and language. | read-only |
| `list_knowledge_bases` | Knowledge bases in a workspace or attached to an agent. | read-only |
| `get_workspace_info` | Workspaces in your account and how many agents each holds. | read-only |
| `list_tenants` | The Chatley accounts your connection can act in. | read-only |
| `get_rate_card` | What each metered operation costs, per unit. | read-only |
| `get_balance` | Current balance and recent metered usage. | read-only |
| `create_agent` | Create an AI voice agent. | changes data |
| `update_agent` | Save changes to an agent as a draft; nothing goes live. | changes data |
| `publish_agent_draft` | Publish a saved draft so it goes live. | changes data |
| `delete_knowledge_base_items` | Delete knowledge bases. | changes data, destructive |
