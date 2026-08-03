# Acceptance Criteria (acceptance-criteria)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Acceptance criteria are predefined conditions that a product, feature, or user story must meet to be considered complete and acceptable by stakeholders. These criteria establish clear, testable requirements that guide development, validate when work is done, and serve as the foundation for automated testing through frameworks like Cucumber, SpecFlow, and Behave. APIs in this space support requirements management, behavior-driven development (BDD), test execution tracking, and agile project management workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/acceptance-criteria/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agile, Behavior Driven Development, Gherkin, Quality Assurance, Requirements, Testing, User Stories

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### GitHub Issues API
GitHub Issues API enables teams to create, manage, and track user stories and acceptance criteria as structured issue records with labels, milestones, and custom fields. Commonly used to attach acceptance criteria directly to issues using body text or checklists in Markdown.

**Human URL:** [https://docs.github.com/en/rest/issues](https://docs.github.com/en/rest/issues)

#### Tags:

 - Issues, User Stories, Requirements, Project Management

#### Properties

- [Documentation](https://docs.github.com/en/rest/issues)
- [Authentication](https://docs.github.com/en/rest/authentication/authenticating-to-the-rest-api)
- [RateLimits](https://docs.github.com/en/rest/overview/resources-in-the-rest-api#rate-limiting)

### Jira Issues API
Jira REST API provides access to issues, user stories, epics, and acceptance criteria stored in custom fields. Teams use Jira to define, link, and track acceptance criteria against development work items throughout the sprint lifecycle.

**Human URL:** [https://developer.atlassian.com/cloud/jira/platform/rest/v3/](https://developer.atlassian.com/cloud/jira/platform/rest/v3/)

#### Tags:

 - Issues, User Stories, Sprint, Project Management

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/jira/platform/rest/v3/)
- [Authentication](https://developer.atlassian.com/cloud/jira/platform/basic-auth-for-rest-apis/)
- [RateLimits](https://developer.atlassian.com/cloud/jira/platform/rate-limiting/)

### Azure DevOps Work Items API
Azure DevOps Work Items REST API enables management of user stories, acceptance criteria, and test cases in Azure Boards. Acceptance criteria are stored as a rich text field on Product Backlog Items and User Story work item types, accessible and updatable via REST.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/](https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/)

#### Tags:

 - Work Items, User Stories, Azure, Project Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/)

### Linear API
Linear GraphQL API provides access to issues, projects, and cycles used by engineering teams to track features and acceptance criteria. Linear supports structured issue descriptions with Markdown, enabling teams to embed acceptance criteria checklists directly on issues.

**Human URL:** [https://developers.linear.app/docs/graphql/working-with-the-graphql-api](https://developers.linear.app/docs/graphql/working-with-the-graphql-api)

#### Tags:

 - Issues, Project Management, GraphQL, Requirements

#### Properties

- [Documentation](https://developers.linear.app/docs/graphql/working-with-the-graphql-api)
- [Authentication](https://developers.linear.app/docs/graphql/working-with-the-graphql-api#authentication)

### TestRail API
TestRail REST API provides access to test cases, test runs, test plans, and results. Teams use TestRail to formally document acceptance criteria as test cases with preconditions, expected results, and step-by-step validation criteria that map directly to user stories.

**Human URL:** [https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API](https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API)

#### Tags:

 - Test Cases, Test Management, Quality Assurance, Requirements

#### Properties

- [Documentation](https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API)
- [Authentication](https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API#authentication)

## Common Properties

- [Website](https://www.agilealliance.org/glossary/acceptance-criteria/)
- [GettingStarted](https://www.mountaingoatsoftware.com/blog/clarifying-the-relationship-between-definition-of-done-and-conditions-of-satisfaction)
- [SpectralRules](rules/acceptance-criteria-spectral-rules.yml)
- [NaftikoCapability](capabilities/requirements-management.yaml)
- [Vocabulary](vocabulary/acceptance-criteria-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Gherkin Syntax Support | Structured Given/When/Then format for writing human-readable acceptance criteria that can be directly executed as automated tests |
| BDD Workflow Integration | Behavior-driven development workflows connecting acceptance criteria to automated test suites via Cucumber, SpecFlow, or Behave |
| Acceptance Criteria Checklists | Structured checklist format for breaking down complex acceptance criteria into discrete, verifiable conditions |
| Requirements Traceability | Linking acceptance criteria to user stories, epics, test cases, and defects for end-to-end traceability |
| Automated Acceptance Testing | Executing acceptance criteria as automated test suites that verify implementation correctness on each code change |
| Stakeholder Collaboration | Shared definition of acceptance criteria between product owners, developers, and QA engineers using accessible, plain-language formats |
| Definition of Done Integration | Incorporating acceptance criteria verification into team Definition of Done checklists and sprint completion gates |
| Test Coverage Reporting | Tracking which acceptance criteria have passing automated tests and which remain untested or failing |

## Use Cases

| Name | Description |
|------|-------------|
| User Story Validation | Define measurable, testable conditions that must be satisfied before a user story is accepted as complete |
| Automated BDD Testing | Convert Gherkin-formatted acceptance criteria into executable test scenarios using Cucumber or SpecFlow |
| Sprint Review Preparation | Use acceptance criteria as the basis for demonstrating completed work to stakeholders during sprint reviews |
| Regression Prevention | Maintain automated acceptance test suites that run on every pull request to prevent regressions |
| API Contract Verification | Use acceptance criteria to define and verify API behavior contracts between producers and consumers |
| Requirements Handoff | Communicate precise feature requirements from product managers to engineers using structured acceptance criteria templates |
| Quality Gate Enforcement | Block deployments or story completion when acceptance criteria tests are failing in CI/CD pipelines |

## Integrations

| Name | Description |
|------|-------------|
| Cucumber | Open-source BDD testing framework that executes Gherkin-formatted acceptance criteria as automated tests |
| SpecFlow | BDD framework for .NET that maps Gherkin feature files to C# step definitions for automated acceptance testing |
| Behave | Python BDD testing library that runs Gherkin acceptance criteria scenarios against Python application code |
| Jira | Project management platform with dedicated Acceptance Criteria field on user story issue types |
| GitHub Issues | Issue tracking with Markdown checklist support for embedding structured acceptance criteria on feature issues |
| Azure DevOps Boards | Microsoft project management with Acceptance Criteria rich-text field on User Story and Product Backlog Item work items |
| TestRail | Test management platform for formalizing acceptance criteria as structured test cases with expected outcomes |
| Linear | Modern issue tracker supporting Markdown acceptance criteria on issues with checklist rendering |

## Artifacts

Machine-readable API specifications and schemas for acceptance criteria management.

### OpenAPI

- [Acceptance Criteria Management](openapi/acceptance-criteria-management.yaml)

### JSON Schema

- [Acceptance Criteria Management Acceptance Criteria List](json-schema/acceptance-criteria-management-acceptance-criteria-list-schema.json)
- [Acceptance Criteria Management Acceptance Criterion](json-schema/acceptance-criteria-management-acceptance-criterion-schema.json)
- [Acceptance Criteria Management Create Acceptance Criterion Request](json-schema/acceptance-criteria-management-create-acceptance-criterion-request-schema.json)
- [Acceptance Criteria Management Create Scenario Request](json-schema/acceptance-criteria-management-create-scenario-request-schema.json)
- [Acceptance Criteria Management Create Test Run Request](json-schema/acceptance-criteria-management-create-test-run-request-schema.json)
- [Acceptance Criteria Management Create User Story Request](json-schema/acceptance-criteria-management-create-user-story-request-schema.json)
- [Acceptance Criteria Management Error Response](json-schema/acceptance-criteria-management-error-response-schema.json)
- [Acceptance Criteria Management Scenario List](json-schema/acceptance-criteria-management-scenario-list-schema.json)
- [Acceptance Criteria Management Scenario](json-schema/acceptance-criteria-management-scenario-schema.json)
- [Acceptance Criteria Management Test Run List](json-schema/acceptance-criteria-management-test-run-list-schema.json)
- [Acceptance Criteria Management Test Run](json-schema/acceptance-criteria-management-test-run-schema.json)
- [Acceptance Criteria Management Update Acceptance Criterion Request](json-schema/acceptance-criteria-management-update-acceptance-criterion-request-schema.json)
- [Acceptance Criteria Management Update User Story Request](json-schema/acceptance-criteria-management-update-user-story-request-schema.json)
- [Acceptance Criteria Management User Story List](json-schema/acceptance-criteria-management-user-story-list-schema.json)
- [Acceptance Criteria Management User Story](json-schema/acceptance-criteria-management-user-story-schema.json)

### JSON Structure

- [Acceptance Criteria Management Acceptance Criteria List](json-structure/acceptance-criteria-management-acceptance-criteria-list-structure.json)
- [Acceptance Criteria Management Acceptance Criterion](json-structure/acceptance-criteria-management-acceptance-criterion-structure.json)
- [Acceptance Criteria Management Create Acceptance Criterion Request](json-structure/acceptance-criteria-management-create-acceptance-criterion-request-structure.json)
- [Acceptance Criteria Management Create Scenario Request](json-structure/acceptance-criteria-management-create-scenario-request-structure.json)
- [Acceptance Criteria Management Create Test Run Request](json-structure/acceptance-criteria-management-create-test-run-request-structure.json)
- [Acceptance Criteria Management Create User Story Request](json-structure/acceptance-criteria-management-create-user-story-request-structure.json)
- [Acceptance Criteria Management Error Response](json-structure/acceptance-criteria-management-error-response-structure.json)
- [Acceptance Criteria Management Scenario List](json-structure/acceptance-criteria-management-scenario-list-structure.json)
- [Acceptance Criteria Management Scenario](json-structure/acceptance-criteria-management-scenario-structure.json)
- [Acceptance Criteria Management Test Run List](json-structure/acceptance-criteria-management-test-run-list-structure.json)
- [Acceptance Criteria Management Test Run](json-structure/acceptance-criteria-management-test-run-structure.json)
- [Acceptance Criteria Management Update Acceptance Criterion Request](json-structure/acceptance-criteria-management-update-acceptance-criterion-request-structure.json)
- [Acceptance Criteria Management Update User Story Request](json-structure/acceptance-criteria-management-update-user-story-request-structure.json)
- [Acceptance Criteria Management User Story List](json-structure/acceptance-criteria-management-user-story-list-structure.json)
- [Acceptance Criteria Management User Story](json-structure/acceptance-criteria-management-user-story-structure.json)

### JSON-LD

- [Acceptance Criteria Management Context](json-ld/acceptance-criteria-management-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [acceptance-criteria-management](capabilities/shared/acceptance-criteria-management.yaml) — 10 operations for acceptance criteria management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [requirements-management](capabilities/requirements-management.yaml) | acceptance-criteria-management | 7 | Product Owner, QA Engineer, Developer |

## Vocabulary

- [Acceptance Criteria Vocabulary](vocabulary/acceptance-criteria-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Acceptance Criteria Spectral Rules](rules/acceptance-criteria-spectral-rules.yml) — 27 rules enforcing acceptance criteria API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
