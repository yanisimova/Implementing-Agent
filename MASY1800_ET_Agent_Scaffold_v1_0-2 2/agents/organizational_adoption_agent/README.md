# Organizational Adoption Readiness Agent — Assignment 7

Version 1.1-student-2026-11-09. This folder is **student-editable** and is based on the course frozen scaffold located elsewhere in this repository. Do not change `core/` or the common intake/output contracts.

Files: `agent_metadata.json`, `specialist_instructions.md`, `cases/primary.json`, `cases/contrast_1.json`, `responses/*_response.json`, `records/revision_and_test_record.md`, `records/agent_record.md`.

For a local working copy, execute from scaffold root:

```bash
python tools/build_prompt.py --agent agents/organizational_adoption_agent --case agents/organizational_adoption_agent/cases/primary.json
python tools/build_prompt.py --agent agents/organizational_adoption_agent --case agents/organizational_adoption_agent/cases/contrast_1.json
python tools/validate_response.py agents/organizational_adoption_agent/responses/primary_response.json
python tools/validate_response.py agents/organizational_adoption_agent/responses/contrast_1_response.json
python tools/check_frozen_core.py
```

Case data and responses are hypothetical instructional test artifacts, **not** claims about identified companies. Prompt packets can be generated from the fixed scaffold; sample outputs already recorded and can be rerun in ChatGPT. Confidential-client use must remain on hold until written permissions and vendor data handling are independently confirmed.
