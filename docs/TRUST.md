# Trust, privacy, and safety

Visual guidance systems operate close to people, workplaces, and potentially
sensitive procedures. Trust cannot be added after the product is built; it must
shape how a workflow is captured, approved, deployed, and evaluated.

## Human authority

Vision CoDev is designed around expert-reviewed procedures. Automated analysis
can assist with organization and observation, but it should not independently
approve work instructions or invent a safety-critical recovery action.

Deployments should define:

- who is qualified to create and approve a procedure;
- who can use, revise, suspend, or retire it;
- when the system must pause or escalate;
- how workers can question or override guidance; and
- which existing procedures remain authoritative.

## Safety boundary

Vision CoDev is not a certified safety system and must not replace approved
safety procedures, required training, qualified supervision, protective
equipment, lockout or isolation controls, or human judgment.

For higher-risk work, an organization should conduct its own hazard analysis,
define fail-safe behavior, validate the complete deployment, and involve the
appropriate safety, legal, privacy, and operational stakeholders.

## Privacy and responsible capture

Recordings may reveal faces, voices, locations, screens, equipment, documents,
or confidential operating methods. A responsible evaluation should apply data
minimization and collect only what the task requires.

Before capture, organizations should decide:

- what may be recorded and why;
- whether participant notice or consent is required;
- how unrelated people and information will be excluded;
- where data may be processed and stored;
- who may access recordings and derived procedures;
- how long each type of data is retained; and
- how access, deletion, and incident requests are handled.

## Organizational separation

The product direction includes separating each organization's data and limiting
access by role and responsibility. The effectiveness of those controls must be
verified in the actual deployment environment; a design intention alone is not
evidence of security.

## Model limitations

Visual and language models can be wrong, inconsistent, or overconfident. Their
performance may change with lighting, camera placement, equipment variants,
clothing, obstructions, accents, noise, network conditions, and unfamiliar
actions.

A responsible workflow should:

- validate on representative examples and people;
- keep an untouched evaluation set where practical;
- report uncertainty and failure cases;
- monitor unnecessary and missed interventions;
- avoid generalizing results beyond the tested conditions; and
- provide a usable path to human help.

## Security reports

Do not publish vulnerability details or sensitive deployment information in a
public issue. Follow the private reporting guidance in the repository's
[security policy](../SECURITY.md).
