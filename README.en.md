# Wugou Orthopaedic Robot Skill

[中文](README.md) | English

Install Wugou product materials in your own AI assistant for product questions, sales introductions and physician product training content. Supports Chinese and English.

## Installation

**In Codex: open the desktop app, start a conversation, then copy and send the entire instruction below.**

```text
$skill-installer Please install the Wugou Product Skill from https://github.com/simpledavid/wugou-robot-product.
SKILL.md is at the repository root. Use wugou-robot-product as the installation name.
```

**Wait for confirmation that installation has completed, then send your first question:**

```text
$wugou-robot-product Give a one-minute introduction to Wugou for a physician.
```

If the skill is not detected after installation, restart Codex and try again. [Official Codex installation guide](https://learn.chatgpt.com/docs/build-skills#install-curated-skills-for-local-use)

Scanning the QR code on a phone opens this installation page. Copy or send the instruction to your computer, then complete installation and ask your question in Codex.

<details>
<summary>Other assistants that support skills, or manual installation</summary>

If your AI assistant supports downloading and installing skills from a repository, send:

```text
Install https://github.com/simpledavid/wugou-robot-product
```

Alternatively, [download the ZIP](https://github.com/simpledavid/wugou-robot-product/archive/refs/heads/main.zip), extract it, and add the complete folder containing `SKILL.md` through your platform's skill import or installation process. The assistant must be able to read the bundled Markdown and PDF files.

Installation steps vary by platform. Pasting a link into an ordinary chat window does not establish that a skill has been installed. After installation, ask: “Give a one-minute introduction to Wugou for a physician.”

</details>

[What you can ask](#what-this-skill-can-do) · [Get the QR code](#brochure-qr-code) · [Original brochure](assets/三折页411.pdf)

## About Wugou

| Item | Information |
| --- | --- |
| Company | Beijing Weigao Technology Co., Ltd. / 北京威高智慧科技有限公司, as printed in the brochure |
| Product | Wugou (吴钩); the company-provided model identification image states WeiZ-01 |
| Company-stated product coverage | Total knee arthroplasty (TKA), total hip arthroplasty (THA) and unicompartmental knee arthroplasty (UKA); model-specific capabilities and registration scope require separate verification |
| Intended users | Sales teams, clinical support staff, physicians and customers |
| Bundled materials | TKA brochure, model identification image, company-provided product information and verified public background sources |
| Contact | The brochure lists (010) 6280-0509 and weiztechnology@weiz.cn |

See the [product facts and source index](references/product-facts.md) for details. The original source documents are primarily in Chinese; the brochure also contains English text.

## What this Skill can do

| Capability | Example question |
| --- | --- |
| Product introduction | “What is Wugou?” “Give a one-minute introduction for a physician.” |
| System overview | “What are the main components?” |
| Product features | “How does planning work?” “What does dynamic tracking do?” |
| TKA workflow overview | “What are the five stages described in the TKA brochure?” |
| Parameter explanation | “What does ±0.5 mm refer to?” |
| Procedure-specific information | “What information is available for TKA, THA and UKA?” |
| Sales and physician product training | “Write a 30-second sales introduction.” “Prepare a physician FAQ.” |
| Contact information | “How can I contact the company about a demonstration or training?” |

The current detailed materials cover TKA features, main components, a five-stage workflow overview and the source of the published bone resection accuracy claim. Detailed THA and UKA workflows, performance parameters and compatibility information still require the respective materials.

The company's stated three-procedure product coverage does not establish that WeiZ-01, or a single registration certificate, covers all three procedures.

Product training currently means introductions, workflow overviews and FAQs. Detailed operational training requires the applicable instructions for use.

## Demonstrations, training and service enquiries

| Action | Current capability | Example request |
| --- | --- | --- |
| Find contact details | Provide the telephone, email and address printed in the brochure | “How can I contact clinical support?” |
| Prepare an enquiry | Organize the information you provide into enquiry points | “Help me prepare a training enquiry.” |
| Submit a request | No booking, training application or repair submission tool is configured | “Can you submit a training request?” |

To use the skill:

1. Tell your AI assistant which product question or procedure you are interested in.
2. It reads the relevant materials and clarifies the model, version or context when those affect the answer.
3. For service enquiries, it provides the available contact details or helps prepare your message. Preparing an enquiry does not mean it has been submitted.

## Runtime

Use an AI assistant that supports skills and can read the bundled Markdown and PDF files. The current product information is included in the package.

This skill runs in the user's AI assistant. The company does not need to operate a separate online chatbot or model service for this distribution method.

## English response examples

**What is Wugou?**

> Wugou is an orthopaedic robot product from Beijing Weigao Technology. The current TKA brochure describes CT-based planning, intraoperative registration, dynamic tracking with gap-balance feedback, and robotic-assisted bone resection. The surgeon completes implant placement. Source: 三折页411.pdf, p. 2.

**What does ±0.5 mm refer to?**

> The English text in the TKA brochure states bone resection accuracy within ±0.5 mm. It does not provide the test conditions or statistical definition. This value should not be treated as registration error, tracking error, angular error or a specification shared by TKA, THA and UKA. Source: 三折页411.pdf, p. 2, “精准执行” / precision execution section.

**What are the THA reaming parameters?**

> The current materials do not specify Wugou's THA reaming parameters. The available detailed brochure covers TKA. The THA module's applicable instructions for use or technical specifications are needed to confirm those parameters.

These examples illustrate wording and source scope. Actual answers must be checked against the relevant materials.

## Wugou information sources

| Item | Current status |
| --- | --- |
| Product facts | Bundled product materials and verified official background sources |
| Original brochure | [三折页411.pdf](assets/三折页411.pdf) |
| Materials index | [Product context and source directory](references/product-context.md) |
| Product API or MCP | No connection is configured |
| Business actions | No booking, training application or repair submission tool is configured |

## Distribution

- GitHub: [simpledavid/wugou-robot-product](https://github.com/simpledavid/wugou-robot-product)
- A local skill folder and ZIP package are also provided.

## Brochure QR code

<img src="assets/wugou-skill-qr.png" alt="QR code for the Wugou Product Skill installation page" width="240">

[Download PNG image](assets/wugou-skill-qr.png) · [Download SVG vector](assets/wugou-skill-qr.svg)

These are two formats of the same QR code, both pointing to this repository. Scan it to read the instructions, then copy the installation instruction into your own AI assistant. Scanning the QR code does not automatically install the skill.

Suggested brochure caption:

> Scan to get the Wugou Product Skill

Use the SVG for print layout. Preserve the white border and aspect ratio, and test the finished layout by scanning it with a phone.

## Version

Current skill version: **0.3.3**, recorded in [skill.json](skill.json). The skill version, product model WeiZ-01, and hardware or software versions are separate identifiers.

The materials were checked on 2026-10-03. The brochure does not state a formal revision. Historical documents do not establish current registration or service status.

To update an installed copy, ask:

> Please update the Wugou Product Skill from https://github.com/simpledavid/wugou-robot-product.

Repository updates do not automatically update installed local copies. Use your assistant platform's update process.

## Use of materials

See the [product context](references/product-context.md) for source scope. The original brochure is included. Actual product requirements must be checked against the applicable formal documents for the model and version.
