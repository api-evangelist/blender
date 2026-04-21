# Blender (blender)
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
