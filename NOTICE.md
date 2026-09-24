# Notice

This agent wraps code AgentMesh did not write.

The skills it carries are the work of the linkedin-skills authors, published at https://github.com/sergebulaev/linkedin-skills. They were copied from commit 5c6192db54db24bf46fab8bbac32f7946daca970.

The skill linkedin-humanizer was left out whole, because its steps use files this agent cannot run or carry: skills/linkedin-humanizer/scripts/detectors.env.example, skills/linkedin-humanizer/scripts/test_detectors.py and skills/linkedin-humanizer/sub-skills/rules-explainer.md.

It is used under the project's own licence, MIT. The full text is in LICENSE, as the authors wrote it.

AgentMesh wrote only what turns it into an agent: spec.json, including the opening of each skill's instructions, this notice and README.md. It changed nothing in the project's code.

No security review was run on the upstream code before it was converted.
