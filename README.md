# Awesome-Forms

# Top Online Form Builders

A curated list of leading online form and survey platforms for data collection, conversational forms, payments, workflows, and experience management.  
**Primary focus: open-source software.**

Commercial / hosted platforms are listed separately for completeness. Open-source alternatives and community tools are emphasized throughout.

---

## SaaS / Hosted Platforms

| Platform | Description | Key Focus |
|----------|-------------|-----------|
| **[Typeform](https://www.typeform.com/)** | Conversational, one-question-at-a-time form and survey platform known for beautiful design, high completion rates, and strong branding options. | Conversational / design-first forms |
| **[Jotform](https://www.jotform.com/)** | Feature-rich form builder with thousands of templates, payments, widgets, approvals, and broad integrations. Extremely versatile for many use cases. | All-in-one forms + templates + payments |
| **[Google Forms](https://forms.google.com/)** | Free, simple form and quiz tool tightly integrated with Google Workspace. Ideal for quick internal surveys and basic data collection. | Free / Google Workspace forms |
| **[Tally](https://tally.so/)** | Modern, Notion-like form builder with a generous free plan, clean UX, and unlimited forms/responses on the free tier. | Simple, unlimited free forms |
| **[Fillout](https://www.fillout.com/)** | Flexible form builder with strong logic, calculations, payments, and a polished Typeform-style experience at a more accessible price. | Modern forms with advanced logic |
| **[Cognito Forms](https://www.cognitoforms.com/)** | Powerful no-code form builder with conditional logic, calculations, repeating sections, and workflow features at competitive pricing. | Advanced logic & calculations |
| **[Formstack](https://www.formstack.com/)** | Enterprise-oriented forms, documents, and e-signature platform with workflow automation, compliance features, and deeper business process tools. | Enterprise forms + documents + workflows |
| **[Zoho Forms](https://www.zoho.com/forms/)** | Part of the Zoho ecosystem — form builder with integrations across Zoho apps, payments, analytics, and multi-channel sharing. | Zoho ecosystem forms |
| **[Paperform](https://paperform.co/)** | Beautifully designed forms with strong product pages, payments, bookings, and e-commerce-style capabilities. | Design + payments + product forms |
| **[Microsoft Forms](https://forms.microsoft.com/)** | Simple form and quiz tool integrated with Microsoft 365 / Teams. Convenient for organizations already in the Microsoft ecosystem. | Microsoft 365 forms & quizzes |

---

## Open-Source Softwares

Online forms have an excellent open-source ecosystem. Several modern projects offer Typeform-style conversational experiences, full data ownership, and self-hosting with no per-response fees.

### Core Frameworks & Form / Survey Platforms

| Project | Description | License | Notes |
|---------|-------------|---------|-------|
| **[Formbricks](https://github.com/formbricks/formbricks)** | Open-source survey and experience management platform. Link, in-app, website, and email surveys with targeting, analytics, and a modern editor. Closest comprehensive open Typeform/Survicate-style alternative. | AGPLv3 | Top modern open survey/forms platform |
| **[HeyForm](https://github.com/heyform/heyform)** | Open-source conversational form builder focused on one-question-at-a-time experiences, quizzes, and polls. Self-hostable via Docker. | AGPL-3.0 | Strong Typeform-style open alternative |
| **[Typebot](https://github.com/baptisteArno/typebot.io)** | Open-source conversational form and chatbot builder with visual flow editor, conditional logic, and integrations. Excellent Typeform-like feel. | Functional Source License (fair-source) | Conversational flows & chat-style forms |
| **[OpnForm](https://github.com/OpnForm/OpnForm)** | Clean, modern open-source no-code form builder with AI form generation, polished UI, and self-hosting support. | AGPL | Polished general-purpose open form builder |
| **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)** | Mature, full-featured open-source survey platform widely used in research, academia, and enterprises. Extremely capable and self-hostable. | GPL | Veteran open-source survey system |
| **[Form.io](https://github.com/formio)** | Developer-focused, JSON-schema-driven form and data management platform. Strong for embedding forms in applications (open-core model). | Open-core | Embeddable / developer form platform |
| **Tripetto** | Form builder with a self-hostable runner/SDK option for embedding conversational forms. | Various / commercial + self-hosted runner | Embeddable form runner |

### Specialized Libraries & Related Tools

| Project | Description | Focus Area |
|---------|-------------|---------|
| **Form libraries for developers** | React Hook Form, Formik, SurveyJS (open parts), JSON Forms, and similar libraries for building custom forms in applications. | Custom / embedded forms |
| **Static form backends** | Formspree alternatives, Basin, or self-hosted endpoints (e.g., with Netlify Forms patterns or custom serverless) for simple HTML forms. | Simple form handling |
| **Survey / quiz engines** | Open quiz and assessment tools that can be self-hosted or embedded. | Quizzes & assessments |
| **PDF & document generation** | Open tools that turn form submissions into PDFs or documents (complementary to Formstack-style workflows). | Post-submission documents |
| **Workflow engines** | n8n, Temporal, or open workflow tools that can process form submissions into multi-step processes. | Form → workflow automation |
| **Analytics & dashboards** | Metabase, Apache Superset, or simple Streamlit apps for analyzing form responses. | Response analytics |

### Additional Notable Open-Source Tools

- **Self-hosted form stacks** — Deploy Formbricks, HeyForm, Typebot, OpnForm, or LimeSurvey with Docker for full data ownership and unlimited responses.
- **WordPress form plugins** — Gravity Forms is commercial, but many open or freemium plugins exist; combined with self-hosted WordPress they offer a hybrid path.
- **Privacy-first / GDPR-focused setups** — All major open-source options above support self-hosting so data never leaves your infrastructure.
- **Embedding & SDKs** — Form.io, Tripetto runner, and custom form libraries for deep product integration.
- **AI-assisted form creation** — Several open projects now include or experiment with AI form generation features.
- **Integration layers** — Webhooks, Zapier/n8n-compatible endpoints, and open APIs for connecting submissions to CRMs, email, and databases.

**Note:** Commercial platforms excel at polished UX, templates, payment gateways, advanced branding, compliance certifications, and zero-ops hosting. Open-source solutions provide complete data ownership, no per-response pricing, and full customization — with Formbricks, HeyForm, Typebot, and OpnForm currently leading the modern open-source form/survey space, and LimeSurvey remaining the most mature full survey platform.

---

## Quick Start Recommendations

| Goal | Recommended Starting Point |
|------|---------------------------|
| Best overall open-source Typeform-style / surveys | **Formbricks** |
| Conversational one-question-at-a-time forms | **HeyForm** or **Typebot** |
| Clean general-purpose open form builder | **OpnForm** |
| Mature, research-grade surveys | **LimeSurvey** |
| Developer / embeddable forms | **Form.io** or form libraries (React Hook Form, etc.) |
| Beautiful conversational hosted forms | **Typeform** |
| Feature-rich templates + payments | **Jotform** |
| Unlimited free simple forms | **Tally** or **Google Forms** |
| Modern forms with strong logic on a budget | **Fillout** or **Cognito Forms** |
| Enterprise forms + documents + workflows | **Formstack** |
| Design + payments + product-style forms | **Paperform** |
| Microsoft 365 integrated forms | **Microsoft Forms** |
| Zoho ecosystem forms | **Zoho Forms** |

---

## Contributing

Contributions, corrections, and new open-source projects are welcome.  
Please open an issue or pull request.

---

**Last updated:** August 2026  
Emphasizing open-source tools while documenting the major commercial platforms for context. Formbricks, HeyForm, Typebot, OpnForm, and LimeSurvey are the leading open-source form and survey platforms, offering strong alternatives to Typeform, Jotform, and similar hosted tools with full data ownership and no per-response fees.
