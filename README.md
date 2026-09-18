# Awesome Enterprise Architect [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated resources for **Sparx Systems Enterprise Architect** (the modeling product):
> add-ins, MDG, scripting, tutorials, and sample models. Not a general enterprise-architecture
> (TOGAF/ArchiMate) list; that lives in the awesome-archimate family spoke.

![Last full sweep: 2026-09](https://img.shields.io/badge/last%20full%20sweep-2026--09-brightgreen)

Part of the awesome-mbse list family (hub: jgsystemsconsulting/awesome-mbse).
While the hub is private, this line stays text-only (no hub hyperlink).

Maintained by [JG Systems Consulting Ltd.](https://github.com/jgsystemsconsulting).
See [Editorial neutrality](CONTRIBUTING.md#editorial-neutrality).

Also: the org holds awesome-sparx-ea as a name-reserve redirect to this list (not a
second catalog). Hyperlink that repo only when it is public; until then keep this
sentence text-only.

## Contents

- [Official product and docs](#official-product-and-docs)
- [Add-ins and MDG technologies](#add-ins-and-mdg-technologies)
- [Scripting, API, and automation](#scripting-api-and-automation)
- [Tutorials and courses](#tutorials-and-courses)
- [Books and papers](#books-and-papers)
- [Sample models](#sample-models)
- [Community and forums](#community-and-forums)
- [Related family lists](#related-family-lists)
- [Install](#install)
- [Usage](#usage)
- [Support](#support)
- [Version](#version)

## Official product and docs

- [Sparx Systems Europe](https://www.sparxsystems.eu/) - EU product and documentation portal for Sparx Systems Enterprise Architect (AU site often WAF-blocks bots) `EA-general` `Sparx-EA` `docs` (2026).
- [Wikipedia: Enterprise Architect (software)](https://en.wikipedia.org/wiki/Enterprise_Architect_%28software%29) - Product overview and history for Sparx Systems Enterprise Architect `EA-general` `Sparx-EA` `docs` (2026).
- [Bellekens.com](https://bellekens.com/) - Community hub for Geert Bellekens Sparx EA add-ins, docs, and related products `EA-general` `Sparx-EA` `docs` (2026).

## Add-ins and MDG technologies

- [Enterprise Architect Toolpack](https://github.com/GeertBellekens/Enterprise-Architect-Toolpack) - Flagship community add-in pack for Sparx EA: navigation, search, and model utilities `EA-general` `Sparx-EA` `plugin` (2026).
- [Enterprise Architect Add-in Framework](https://github.com/GeertBellekens/Enterprise-Architect-Add-in-Framework) - C# framework for building Sparx EA add-ins on the COM API `EA-general` `Sparx-EA` `plugin` (2026).
- [UML Tooling Framework](https://github.com/GeertBellekens/UML-Tooling-Framework) - Shared UML case-tool framework used by Bellekens Sparx EA add-ins `UML` `Sparx-EA` `plugin` (2026).
- [Enterprise Architect Shapescript Library](https://github.com/GeertBellekens/Enterprise-Architect-Shapescript-Library) - ShapeScripts for custom MDG diagram rendering in Sparx EA `EA-general` `Sparx-EA` `plugin` (2025).
- [Enterprise Architect MDG Technologies](https://github.com/GeertBellekens/Enterprise-Architect-MDG-Technologies) - MDG technology packs extending Sparx EA profiles and toolboxes `EA-general` `Sparx-EA` `plugin` (2026).
- [hoTools](https://github.com/Helmut-Ortmann/EnterpriseArchitect_hoTools) - Large C# add-in toolset for Sparx EA modeling, search, and productivity `EA-general` `Sparx-EA` `plugin` (2025).
- [IDL4 Enterprise Architect](https://github.com/rticommunity/idl4-enterprise-architect) - RTI add-in generating IDL 4 / Connext DDS artifacts from Sparx EA models `other-lang` `Sparx-EA` `plugin` (2018).
- [GoatAssociations](https://github.com/SlavekRydval/GoatAssociations) - Association-oriented add-in for Sparx EA UML modeling workflows `UML` `Sparx-EA` `plugin` (2017).
- [GoatJira](https://github.com/SlavekRydval/GoatJira) - Bidirectional JIRA and Sparx EA repository synchronization add-in `EA-general` `Sparx-EA` `plugin` (2018).
- [ActiveDiagrams](https://github.com/SlavekRydval/ActiveDiagrams) - Active diagram add-in bridging Microsoft Word and Sparx EA `EA-general` `Sparx-EA` `plugin` (2017).
- [ea-datagov MDG](https://github.com/wpkramer/ea-datagov) - Data-governance MDG technology for Sparx EA repositories `EA-general` `Sparx-EA` `plugin` (2018).
- [ea-ui-tools MDG](https://github.com/bart-the-butcher/ea-ui-tools) - MDG technology for UI modeling diagrams inside Sparx EA `UML` `Sparx-EA` `plugin` (2025).
- [SpecIF EA Plugin](https://github.com/oalt/MDD4All.SpecIF.Apps.EaPlugin) - SpecIF interoperability plugin for Sparx Systems Enterprise Architect `EA-general` `Sparx-EA` `plugin` (2024).
- [EIP icons for Enterprise Architect](https://github.com/hwestphal/eip-ea-icons) - Enterprise Integration Patterns icon set for Sparx EA diagrams `UML` `Sparx-EA` `plugin` (2014).
- [ea-model-validator-framework](https://github.com/ftsrg/ea-model-validator-framework) - Extensible model validation framework for Sparx EA repositories `EA-general` `Sparx-EA` `plugin` (2023).
- [sparx4edgy23 MDG](https://github.com/yafbv/sparx4edgy23) - Free EDGY 2023 MDG technology and `.qea` toolkit for Sparx EA `EA-general` `Sparx-EA` `has-model` `plugin` (2026).
- [ea_c4ext MDG](https://github.com/atalarczyk/ea_c4ext) - Extended C4 model MDG technology for Sparx Systems Enterprise Architect `UML` `Sparx-EA` `plugin` (2025).
- [EA Navigator](https://bellekens.com/ea-navigator/) - Commercial navigation add-in for fast traversal of Sparx EA models `EA-general` `Sparx-EA` `plugin` `paid` (2026).
- [EAAddinTemplate](https://github.com/workingmatt/EAAddinTemplate) - Minimal starter template for building a Sparx EA add-in `EA-general` `Sparx-EA` `plugin` (2023).
- [EASwagger](https://github.com/SvDo70/EASwagger) - Generate OpenAPI/Swagger definitions from API models in Sparx EA `other-lang` `Sparx-EA` `plugin` (2025).
- [vienna-add-in-BE](https://github.com/GeertBellekens/vienna-add-in-BE) - Maintained fork of the Vienna add-in for Sparx EA UML work `UML` `Sparx-EA` `plugin` (2023).
- [itemis EA Bridge VS Code companion](https://github.com/itemisCREATE/ea-bridge-vscode) - Companion repository for the itemis EA Bridge VS Code extension `EA-general` `Sparx-EA` `plugin` (2026).
- [roundtrip-add-in](https://github.com/bayeslife/roundtrip-add-in) - Bidirectional model and filesystem synchronization add-in for Sparx EA `EA-general` `Sparx-EA` `plugin` (2017).

## Scripting, API, and automation

- [Enterprise Architect VBScript Library](https://github.com/GeertBellekens/Enterprise-Architect-VBScript-Library) - VBScript automation wrappers and helpers for the Sparx EA COM API `EA-general` `Sparx-EA` `script` (2026).
- [EA RefData Splitter](https://github.com/GeertBellekens/EARefDataSplitter) - Split and manage Sparx EA reference-data script packs `EA-general` `Sparx-EA` `tool` (2026).
- [gobravedave Enterprise-Architect scripts](https://github.com/gobravedave/Enterprise-Architect) - VBScript snippets that extend Sparx EA automation workflows `EA-general` `Sparx-EA` `script` (2023).
- [Sparx EA C# API Wrapper](https://github.com/EamonnJCasey/Sparx-Enterprise-Architect-Wrapper) - C# wrapper around the Sparx EA COM automation API `EA-general` `Sparx-EA` `script` (2018).
- [eamodeltransfer](https://github.com/krequena/eamodeltransfer) - Library for transferring model content between Sparx EA repositories `EA-general` `Sparx-EA` `tool` (2022).
- [sparxea2confluence](https://github.com/slookin/sparxea2confluence) - Export Sparx EA diagrams into Confluence pages `EA-general` `Sparx-EA` `tool` (2026).
- [EABaatScripts](https://github.com/DeBAAT/EABaatScripts) - JavaScript scripts for automating Sparx Systems Enterprise Architect `EA-general` `Sparx-EA` `script` (2025).
- [avzdk/sparx Python DB framework](https://github.com/avzdk/sparx) - Python framework for working with Sparx EA objects stored in a database `EA-general` `Sparx-EA` `script` (2025).
- [enterprise-architect-mcp](https://github.com/DITEC-Mracka/enterprise-architect-mcp) - Read-only MCP server over Sparx EA `.qea` model exports `EA-general` `Sparx-EA` `tool` (2026).
- [beeatlas-sparx-adapter](https://github.com/tech-beeline/beeatlas-sparx-adapter) - Node REST API adapter over a Sparx EA PostgreSQL repository `EA-general` `Sparx-EA` `tool` (2026).
- [ea-mcp-toolkit](https://github.com/hdjebar/ea-mcp-toolkit) - MCP servers for browsing Sparx EA models from Claude on macOS `EA-general` `Sparx-EA` `tool` (2026).
- [sparx-ea-scripts](https://github.com/Mitchel85/sparx-ea-scripts) - EA 17.x JavaScript scripting engine work for ADMBw/NAFv4 profiles `EA-general` `Sparx-EA` `script` (2026).
- [sparxea-mcp-server](https://github.com/knglumt/sparxea-mcp-server) - Python MCP server for interacting with Sparx Systems Enterprise Architect `EA-general` `Sparx-EA` `tool` (2026).
- [spxea-mcp](https://github.com/codebureau/spxea-mcp) - C# MCP server bridging agents to Sparx Systems Enterprise Architect `EA-general` `Sparx-EA` `tool` (2026).
- [Sparx-EA-Scripts-and-Tools](https://github.com/MatthiasVanDE/Sparx-EA-Scripts-and-Tools) - Collection of scripts and helper tools for Sparx EA automation `EA-general` `Sparx-EA` `script` (2018).
- [biz.dfch.PS.EnterpriseArchitect.Scripts](https://github.com/dfensgmbh/biz.dfch.PS.EnterpriseArchitect.Scripts) - PowerShell scripts for automating Sparx Systems Enterprise Architect `EA-general` `Sparx-EA` `script` (2018).
- [SQL-Sparx](https://github.com/lawlermj1/SQL-Sparx) - SQL queries to profile and inspect a Sparx EA repository instance `EA-general` `Sparx-EA` `script` (2022).
- [SSProCloud-Docker](https://github.com/IDI-Systems/SSProCloud-Docker) - Docker setup for hosting Sparx Pro Cloud Server `EA-general` `Sparx-EA` `tool` (2022).
- [qea-diff-merge](https://github.com/ludw1/qea-diff-merge) - Browser prototype for diff and merge of Sparx EA `.qea` SQLite models `EA-general` `Sparx-EA` `tool` (2026).
- [LieberLieber LemonTree](https://www.lieberlieber.com/lemontree/) - Commercial model diff and merge product widely used with Sparx EA `EA-general` `Sparx-EA` `tool` `paid` (2026).
- [setup-LemonTree.Automation](https://github.com/LieberLieber/setup-LemonTree.Automation) - GitHub Action setup for LieberLieber LemonTree.Automation with Sparx EA `EA-general` `Sparx-EA` `tool` (2024).
- [ShapeScriptMagic](https://github.com/schmitze87/ShapeScriptMagic) - Tooling to manipulate ShapeScripts inside Sparx EA MDG technologies `EA-general` `Sparx-EA` `tool` (2020).
- [ea-linux-wine-setup](https://github.com/andresgarcia0313/ea-linux-wine-setup) - Wine install automation for running Sparx EA 17 on Linux `EA-general` `Sparx-EA` `script` (2026).
- [eapy](https://github.com/ovidiupescar/eapy) - Python proof-of-concept automating Sparx EA and requirement test generation `EA-general` `Sparx-EA` `script` (2026).
- [genivi-doc-generator](https://github.com/gunnarx/genivi-doc-generator) - Template-driven Word document generator from Sparx EA UML models `UML` `Sparx-EA` `tool` (2016).
- [eaxmi2neo4j](https://github.com/tomasrollo/eaxmi2neo4j) - Load XMI exported from Sparx EA into a Neo4j graph database `EA-general` `Sparx-EA` `script` (2017).

## Tutorials and courses

No verified standalone tutorial entries in the seed inventory yet. Prefer Sparx Systems
Europe docs and the official YouTube channel under Community until dedicated courses land.

## Books and papers

- [scripting-ea book materials](https://github.com/AgileHealthInformatics/scripting-ea) - Companion materials for the Sparx EA scripting book (scripts and examples) `EA-general` `Sparx-EA` `book` (2025).
- [Simple SysML for Beginners](https://www.goodreads.com/book/show/52087615-simple-sysml-for-beginners) - David Hetherington book teaching SysML with Sparx Systems Enterprise Architect `SysML-general` `Sparx-EA` `book` `paid` (2020).

## Sample models

- [Simple SysML for Beginners (EA examples)](https://github.com/asukumari/sysml-for-beginners_david-hetherington) - Example model pack accompanying the Hetherington Sparx EA SysML book `SysML-general` `Sparx-EA` `has-model` `book` (2021).
- [rocketSystemModel](https://github.com/bff89/rocketSystemModel) - Downloadable `Rocket System.eapx` Sparx EA SysML sample model `SysML-general` `Sparx-EA` `has-model` `case-study` (2024).
- [hearingEnhancer](https://github.com/bff89/hearingEnhancer) - Downloadable `Hearing Enhancer System.eapx` Sparx EA SysML sample `SysML-general` `Sparx-EA` `has-model` `case-study` (2024).
- [BHoughtaling SparxEA](https://github.com/BHoughtaling/SparxEA) - Package of Sparx EA models, MDG technologies, and scripts `EA-general` `Sparx-EA` `has-model` `script` (2015).
- [KDOT_CollectorModel](https://github.com/gontek/KDOT_CollectorModel) - Public Sparx EA geodatabase design model pack `EA-general` `Sparx-EA` `has-model` `case-study` (2021).
- [FinanceRequirementsManagement](https://github.com/brusselsdude/FinanceRequirementsManagement) - FinTech requirements-management model with XMI import for Sparx EA `EA-general` `Sparx-EA` `has-model` `case-study` (2026).

## Community and forums

- [Sparx Systems YouTube](https://www.youtube.com/@SparxSystems) - Official Sparx Systems channel for Enterprise Architect product videos and demos `EA-general` `Sparx-EA` `video` (2026).

## Related family lists

Enterprise-architecture *discipline* material (ArchiMate viewpoints, Archi tool,
TOGAF-aligned EA modeling) belongs on [awesome-archimate](https://github.com/jgsystemsconsulting/awesome-archimate),
not here. Sparx product tooling, add-ins, MDG, API/scripting, tutorials, and
Sparx-native sample models belong on this list. Cross-link only; never copy full
entries between the two.

Sibling MBSE product lists in the same family include awesome-mbse (hub; private,
text-only mention while private), awesome-capella, awesome-sysml-v2, and
awesome-stpa. Do not hyperlink private hub or name-reserve repos.

## Contributing

Contributions welcome: see [CONTRIBUTING.md](CONTRIBUTING.md) for the inclusion bar,
entry format, and tag vocabulary.

## Install

Nothing to install. This list is a curated index: browse it here on GitHub,
or clone it:

```bash
git clone https://github.com/jgsystemsconsulting/awesome-enterprise-architect.git
```

## Usage

1. Open the Contents at the top and jump to a section, or search the page with
   your browser's find function.
2. Open any entry's link to reach the upstream resource; the list never
   re-hosts content.
3. To suggest a resource or report a defect, use the Support channels below
   (or open a pull request that follows CONTRIBUTING.md).

## Support

- Bug or dead link: open an issue on this repository
- Suggest a resource: open a pull request that follows CONTRIBUTING.md, or open an issue
- Security issues: [private security advisory](https://github.com/jgsystemsconsulting/awesome-enterprise-architect/security/advisories/new)
  (see [SECURITY.md](SECURITY.md))
- Licence: this list is [CC0 1.0 Universal](LICENSE). Linked resources keep their
  own licences. Licence enquiries: [labs licensing form](https://labs.jgsystemsconsulting.com/licensing.html).

## Version

Current release: **0.1.0-private** (2026-09-18). See [CHANGELOG.md](CHANGELOG.md).
