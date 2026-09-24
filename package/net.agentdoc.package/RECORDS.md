# The records this agent must leave

This is the contract. The agent leaves the following behind, on
every run.

- the skill followed for the task and every command run while following it, word for word, with its exit code — at `*/commands.txt`
- every file delivered, listed in pieces.json in the job folder

An agent that leaves less than this does not do this job,
whatever else it does well.
