# Notice

This agent wraps code AgentMesh did not write.

The skills it carries are the work of the linkedin-skills authors, published at https://github.com/sergebulaev/linkedin-skills. They were copied from commit 5c6192db54db24bf46fab8bbac32f7946daca970.

This agent's own version is 1.0.2; it counts changes to this agent. The upstream version it was made from is commit 5c6192d.

The skill linkedin-humanizer was left out whole, because its steps use what this agent cannot run or carry, with no way to do the job without it: skills/linkedin-humanizer/scripts/detectors.env.example, skills/linkedin-humanizer/scripts/test_detectors.py, skills/linkedin-humanizer/sub-skills/rules-explainer.md, the Python file scripts/check_config.py and the Python file scripts/test_detectors.py.

It is used under the project's own licence, MIT. The full text is in LICENSE, as the authors wrote it.

AgentMesh wrote only what turns it into an agent: spec.json, including the opening of each skill's instructions, this notice and README.md. It changed nothing in the project's code.

No security review was run on the upstream code before it was converted.
