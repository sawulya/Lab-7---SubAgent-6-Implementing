# Assignment 7 — Organizational Adoption Agent

Student-editable specialization of the frozen course scaffold. Original FROZEN CORE files were not changed.

## Run and validate
From repository root:

```bash
python tools/check_frozen_core.py
python tools/build_prompt.py --agent agents/organizational_adoption_agent --case agents/organizational_adoption_agent/cases/primary.json
python tools/build_prompt.py --agent agents/organizational_adoption_agent --case agents/organizational_adoption_agent/cases/contrast_1.json
python tools/validate_response.py agents/organizational_adoption_agent/responses/primary_response.json
python tools/validate_response.py agents/organizational_adoption_agent/responses/contrast_1_response.json
```

Open the prompt packets in `work/` and compare them with saved representative JSON responses. For independent repetition, submit packets to ChatGPT and save new JSON responses before validation.

**Caution:** The organizational profiles are fictional teaching scenarios. Saved test responses are reasoned representative analyses, not audited organizational findings or independently timestamped API runtime traces. The supplied validator checks structure only. GitHub branch/commit must be populated once the user publishes the working copy.
