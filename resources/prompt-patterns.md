# Prompt Patterns

## Structured extraction
Ask for fields explicitly present in the supplied text; return null for missing fields; do not infer. Validate the returned JSON against an application schema.

## Classification
Provide an allowed category list, request one category, evidence and a confidence band. Define an `other` outcome.

## Grounded Q&A
Instruct the model to answer only from supplied context, cite source IDs, and say when the context does not contain the answer.

## Safety
Delimit user content and retrieved documents as untrusted. Never treat retrieved text as privileged instructions. Validate outputs and enforce permissions in application code.
