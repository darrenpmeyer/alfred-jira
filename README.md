# alfred-jira 2.0

Alfred Workflow for common Jira Cloud lookup tasks

Provides two Alfred keywords that open Jira Cloud pages in your default
browser:

- `jira`
	- with argument, performs a "Quick Search"
	- with no argument, opens "Your Work" page
- `jql` -- runs the provided JQL query

## Configuration

You must provide the Workflow Environment Variable `base_url`; this should be
the base URL of your Jira Cloud (usually `https://yourorg.atlassian.net` or
`https://yourorg.atlassian.net/jira`).

Other Workflow Environment Variables can be adjusted to specify non-default
paths to the browse, query, and JQL endpoints.