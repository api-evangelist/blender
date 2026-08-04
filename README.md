# Blender (blender)

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

Blender is the free and open source 3D creation suite supporting the entirety of the 3D pipeline including modeling, rigging, animation, simulation, rendering, compositing, motion tracking, video editing, and game creation. Blender's Python API provides extensive scripting capabilities for automation, tool development, and addon creation, enabling developers to extend Blender with custom functionality. The project is governed by the Blender Foundation and maintained at blender.org.

**URL:** [https://www.blender.org](https://www.blender.org)

**License:** [GPL-2.0-or-later](https://www.blender.org/about/license/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - 3D, Animation, Game Development, Modeling, Open Source, Python, Rendering, VFX

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-21

## APIs

### Blender Python API
The Blender Python API (bpy) provides Python access to Blender's internal data, operators, and UI components. It enables developers to automate tasks, create addons, build custom tools, manipulate scene data, interact with the render pipeline, and extend Blender's interface.

**Human URL:** [https://docs.blender.org/api/current/](https://docs.blender.org/api/current/)

#### Tags:

 - Addons, Automation, Open Source, Python, Scripting

#### Properties

- [Documentation](https://docs.blender.org/api/current/)
- [GitHub](https://github.com/blender/blender)
- [Getting Started](https://docs.blender.org/api/current/info_quickstart.html)
- [Tutorials](https://docs.blender.org/api/current/info_tips_and_tricks.html)
- [JSON Schema - Addon Manifest](json-schema/blender-addon-manifest-schema.json)
- [JSON Schema - bpy Operator](json-schema/blender-bpy-operator-schema.json)
- [JSON-LD Context](json-ld/blender-context.jsonld)
- [Example - Addon Manifest](examples/blender-addon-manifest-example.json)
- [Example - bpy Operator](examples/blender-bpy-operator-example.json)

### Blender Extensions Platform
The Blender Extensions Platform (extensions.blender.org) provides a curated repository of addons, themes, and node presets for Blender. Developers can publish addons with structured metadata and versioning.

**Human URL:** [https://extensions.blender.org](https://extensions.blender.org)

#### Tags:

 - Addons, Extensions, Marketplace, Open Source

#### Properties

- [Documentation](https://docs.blender.org/manual/en/latest/extensions/index.html)
- [Portal](https://extensions.blender.org)

## Common Properties

- [Website](https://www.blender.org/)
- [Documentation](https://docs.blender.org/)
- [Getting Started](https://docs.blender.org/api/current/info_quickstart.html)
- [Community](https://www.blender.org/community/)
- [Support](https://www.blender.org/support/)
- [GitHub Organization](https://github.com/blender)
- [GitHub](https://github.com/blender/blender)
- [Blog](https://www.blender.org/news/)
- [Training](https://www.blender.org/training/)
- [FAQ](https://www.blender.org/support/faq/)
- [Release Notes](https://developer.blender.org/docs/release_notes/)
- [Package Registry](https://extensions.blender.org)
- [Spectral Rules](rules/blender-spectral-rules.yml)
- [Naftiko Capability](capabilities/blender-python-api.yaml)
- [Vocabulary](vocabulary/blender-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Python Scripting (bpy) | The bpy module provides access to Blender's internal data model, allowing Python scripts to create, read, update, and delete scene objects, materials, animations, constraints, and render settings. |
| Operator Framework | Blender's operator system allows Python developers to create custom operators (commands) accessible from menus, panels, keyboard shortcuts, and scripts. |
| Addon Development | Blender addons are Python packages extending functionality across modeling, rigging, animation, rendering, import/export, and UI. Distributed via the Extensions Platform or bundled directly. |
| Node Groups and Geometry Nodes | Geometry Nodes and Shader Nodes provide visual programming for procedural modeling and materials, scriptable via the Python API. |
| Render Pipeline Integration | Python API integrates with Blender's Cycles and EEVEE render engines for batch rendering, render farm integration, and custom render pipeline control. |
| Command-Line Interface | Blender can be invoked headlessly via CLI for batch rendering, script execution, and pipeline automation without a GUI. |
| Asset Library System | Blender 3.x+ includes an asset library system with Python API support for managing and accessing reusable 3D assets across projects. |

## Use Cases

| Name | Description |
|------|-------------|
| Pipeline Automation | VFX and animation studios automate Blender production pipelines using Python scripts for batch rendering, asset processing, and scene assembly. |
| Addon Development | Developers create custom tools and plugins extending Blender's functionality for modeling, rigging, simulation, and export workflows. |
| Headless Rendering | Blender is used for headless server-side rendering via CLI and Python scripts in cloud rendering pipelines and automated content generation workflows. |
| Procedural Content Generation | Python scripts and Geometry Nodes enable procedural generation of 3D assets for games, VFX, and architectural visualization. |
| Education and Research | Universities, research labs, and educators use Blender's Python API for 3D visualization, scientific rendering, and computer graphics research. |

## Integrations

| Name | Description |
|------|-------------|
| Cycles X Render Engine | Blender's built-in path-tracing render engine with Python API access for controlling render settings, passes, and denoising. |
| USD (Universal Scene Description) | Blender supports import and export of Pixar USD scenes, enabling pipeline integration with VFX and game development workflows. |
| glTF 2.0 | Blender has built-in glTF 2.0 import/export support with Python API access, enabling web, AR/VR, and game engine pipelines. |
| OpenVDB | Blender supports OpenVDB for volumetric simulation and rendering, with Python API access to volume data and simulation parameters. |
| ACES Color Management | Blender integrates with OpenColorIO for ACES and professional color pipeline support in VFX productions. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
