# Selected work and current direction

## Australian Business Finder

**Type:** publicly installable Australian business-discovery skill

**Status:** public beta; [source and guide](https://github.com/JakeMarchin-Vincent/aus-business-finder)

Give it a business type and an Australian place. It finds candidates and links the businesses’ own pages, separating an advertised service area from a published address. It does not independently certify that a business is trading, has a shop open, or is available; it does not contact anyone.

For example, [an Adelaide refrigeration-repair search](https://github.com/JakeMarchin-Vincent/aus-business-finder#example-from-a-local-test) returned three candidates whose pages advertised that service to Adelaide. Earlier tests caught overconfident physical-shop and address claims, so the release deliberately says **sourced candidate**, not verified business. [Evidence and limits](https://github.com/JakeMarchin-Vincent/aus-business-finder/blob/main/EVIDENCE.md) explain what was tried and what remains unproven.

Install in Hermes: `hermes skills install JakeMarchin-Vincent/aus-business-finder/skills/aus-business-finder-mv`. The public package was installed in a clean, isolated Hermes home; a live model run in that credential-free home was not performed. Hermes and the hosted model supply the runtime and inference; the Australian search procedure and evaluation are the authored contribution.

A maintained business dataset and approved agent-to-business actions are **future possibilities**, not features of this release.

## MVgrillz

**Type:** reusable planning skill

**Status:** working privately in Hermes; not publicly released

Once the foundations of an idea are established, MVgrillz works through the important planning questions itself, follows the decisions they create, and returns an overall proposed plan for the person to review and change.

It is not simply a questionnaire handed back to the user. Recommended answers remain recommendations, not permission to spend, publish or act on someone else's behalf.

**Portfolio focus:** demonstrate a clear starting brief, the resulting plan and how a changed constraint changes the plan. Broader compatibility and general improvement claims are not established.

## MVskill-ops

**Type:** reusable skill-creation and improvement skill

**Status:** working privately in Hermes; not publicly released

Helps a person turn a recurring workflow into a reusable skill: establish the job, check existing options, research gaps, write the package, assess examples and improve it from observed failures.

It is developed in Skill Factory and can also help improve projects outside it, such as hermgainz. It is not an automatic publishing service, and skill creation does not require full autonomy.

**Portfolio focus:** show one concrete before-and-after skill example and explain the changes supported by actual evidence. A useful procedure is not a guarantee that every skill it creates is effective.

## hermgainz

**Type:** standalone fitness-coaching skill

**Status:** development candidate; not publicly released

Provides in-chat guidance for training, mobility, recovery and everyday nutrition, adapting to the person's goal, equipment, time and reported activity.

It remains a separate project. It does not require an app, plugin or automatic health logging. It is not a certified trainer, medical service or clinically validated programme.

**Portfolio focus:** safe synthetic examples of planning and follow-up, with clear boundaries. Broader behaviour and qualified safety review remain pending; no real-person transformation claim is made.

## Our own agent

**Type:** original-agent project

**Status:** direction established; first workflow not selected

The aim is to develop an original agent that does something useful and helps us learn the underlying decisions. Existing models and supporting libraries may be reused and credited.

This is distinct from the existing Hermes agents helping us with the portfolio. No completed agent or performance result is claimed here.

## Research and experiments

**Type:** research and learning

**Status:** ongoing research; public write-ups added when ready

The AI Research Engineer Lab investigates specific questions that can improve our skills and agent work. Not every change needs a formal research project.

The portfolio will distinguish an idea, a proposed experiment and an executed finding. Useful negative results belong here too, provided the evidence can be shared safely.

## Skill Factory

**Role:** private development workshop, not a new public app

Skill Factory holds original skills such as MVgrillz and MVskill-ops and the resources used to improve them. It supports the portfolio; it is not the portfolio itself. hermgainz keeps its separate home.

Public packages and examples are shared selectively rather than copying the private workshop wholesale.
