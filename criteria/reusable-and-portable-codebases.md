---
order: 3
---

# Create reusable and portable code

## Requirements

* The codebase MUST be developed to be reusable in different contexts.
* The codebase MUST be independent from any secret, undisclosed, proprietary or non-open licensed code or services for execution and understanding.
* The codebase MUST be in use by multiple parties.
* The roadmap SHOULD be influenced by the needs of multiple parties.
* Code SHOULD be general purpose and SHOULD be configurable.
* Codebases SHOULD include a [publiccode.yml](https://github.com/italia/publiccode.yml) metadata description so that they're easily discoverable.
* Code and its documentation SHOULD not contain situation-specific information. For example, personal and organizational data as well as tokens and passwords used in the production system should never be included.

## Why this is important

* Enables other policy makers, developers and designers to reuse what you've developed, to test it, to improve it and contribute those improvements back leading to better quality, cheaper maintainability and higher reliability.
* Makes the code easier for new people to understand (as it's more general).
* Makes it easier to control the mission, vision and scope of the codebase because the codebase is thoughtfully and purposefully designed for reusability.
* Codebases used by multiple parties have broad enough value to be Public Code and are more likely to benefit from a self-sustaining community..

## What this does not do

* Get others to reuse the codebase.
* Build a community.
* Shift responsibility for documentation, support, bug-fixing, etc. to another party.

## How to test

* Ask someone in a similar role at another organization if they could reuse your codebase and what that would entail.
* Codebase is in use by multiple parties or in multiple contexts.

## Policy makers: what you need to do

* Document your policy with enough clarity and detail that it can be understood outside of its original context.
* Make sure your organization is listed as a known user by the project.

## Management: what you need to do

* Make sure that stakeholders and business owners understand that reusability is an explicit goal of the project as it reduces technical debt and provides sustainability for the codebase.

## Developers and designers: what you need to do

* Source should be designed for reuse by other users and organizations.
* Source should be designed to solve a general problem instead of a specific one.
* Someone in a similar organization facing a similar problem should be able to use your solution.

## Further reading

* [Making source code open and reusable](https://www.gov.uk/service-manual/technology/making-source-code-open-and-reusable) by the UK Government Digital Service.
