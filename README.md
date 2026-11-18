# T2D_MCP_Server(T2D Compass)

T2D Compass is a research-support application that helps users find completed Type 2 diabetes interventional studies and inspect source-linked evidence from ClinicalTrials.gov.

The system is designed to help researchers review public registry information, study context, results availability, missing information, and review flags.

T2D Compass is a find-and-retrieve research agent. It does not diagnose patients, recommend treatments, rank interventions, or establish comparative clinical effectiveness.

#Purpose
T2D Compass supports a source-first research workflow:

Find candidate completed Type 2 diabetes interventional studies.

Retrieve evidence cards for selected studies.

Inspect study design, population, enrollment, interventions, outcomes, timeframes, and results availability.

Review the original ClinicalTrials.gov record.

Export search results, evidence cards, and assistant traces.

#Scope
The final application uses two research tools:

find_completed_trials

get_trial_evidence_card

The application supports:

Searching for completed Type 2 diabetes-related interventional studies.

Optional intervention filtering.

Retrieval by NCT identifier.

Source-linked evidence cards.

Assistant-supported search and retrieval.

JSON and trace exports.

Reporting of missing information, warnings, and search limitations.
