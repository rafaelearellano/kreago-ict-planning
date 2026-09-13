# KREAGO ICT Planning

KREAGO ICT Planning is an early-stage prototype focused on improving how physical ICT infrastructure is planned, reviewed, and quantified before installation.

The project is being developed around real field problems found in low-voltage and telecommunications infrastructure, including pathway constraints, cable-distance limits, coordination conflicts, device quantities, material takeoff, and constructability.

## Current Focus

The prototype is being developed to support workflows such as:

- Drawing and plan analysis
- ICT device identification
- Quantity takeoff
- Bill of Materials preparation
- Pathway and routing evaluation
- Engineering-rule checks
- Early identification of coordination issues
- Human review and validation of AI-assisted results

## Design Approach

KREAGO is not intended to autonomously design telecommunications infrastructure.

The intended workflow is:

```text
Plans / Project Information
          ↓
AI-assisted interpretation
          ↓
Engineering rules evaluation
          ↓
Warnings / quantities / alternatives
          ↓
Human technical validation
          ↓
Reports and project outputs

The goal is to support engineering and construction decisions while keeping technical review and final judgment with the user.

Problems Being Addressed

Physical ICT infrastructure can be affected by issues that are difficult or expensive to correct after installation begins.

Examples include:

Copper horizontal cabling exceeding allowable distances
Poor MDF/IDF assignment
Missing or poorly located pull points
Excessive pathway bends
Conduit and pathway capacity issues
Conflicts with electrical, HVAC, fire protection, and other building systems
Incorrect or incomplete device quantities
Material discrepancies between drawings and field conditions
Rework caused by planning decisions that are technically possible on paper but difficult to build

KREAGO is being developed to identify more of these conditions earlier in the planning process.

Development Status

Prototype / Work in Progress

The project is currently under active development.

Current work includes:

User interface development
Drawing-analysis workflows
Device and symbol classification
Quantity extraction
Engineering-rule logic
Reporting and validation workflows
Evaluation of local AI models for software development and technical analysis

The internal application source code and engineering-rule implementation are maintained separately from this public repository.

Technical Direction

The project is being developed around a modular architecture that separates:

Project and drawing inputs
Information extraction
Engineering rules
Spatial and pathway analysis
Engineering evaluation
Alternative generation
Human validation
Reports, quantities, BOMs, and documentation

The intended logic is:

AI interprets → rules evaluate → software proposes → engineer validates

Planned Capabilities

Future development may include:

PDF and drawing interpretation
Symbol and device recognition
Automated quantity takeoff
Cable and pathway-length evaluation
MDF/IDF assignment assistance
Pathway geometry checks
Conduit and support-rule evaluation
Coordination alerts
BOM generation
Comparison of design alternatives
Traceable engineering-rule results
AI-assisted review of project documentation
Technology

The prototype currently uses and evaluates technologies including:

Python
FastAPI
React
TypeScript
HTML / CSS
Local and cloud-based AI models
Computer vision and document-processing tools
Rule-based engineering analysis
Git-based version control

The final technology stack may change as the prototype develops.

Project Background

KREAGO is being developed from practical experience with ICT and low-voltage infrastructure in environments such as airports, educational facilities, communications rooms, secure spaces, and other complex buildings.

The project is intended to convert recurring field and coordination problems into repeatable software-assisted checks that can be applied earlier in project planning.

Public Repository Scope

This repository is intended to document the development and technical direction of the project.

It may include:

Architecture diagrams
Selected screenshots
Development notes
Public demonstrations
Technical concepts
Roadmap information
Non-confidential examples

It does not currently contain the complete application source code, proprietary engineering-rule implementation, confidential project documents, or customer information.

Roadmap

Near-term development priorities include:

Improve drawing-analysis reliability
Expand device and symbol classification
Improve quantity takeoff
Add traceable engineering-rule checks
Improve reporting and validation
Test workflows against representative ICT projects
Develop a functional demonstration suitable for technical review
Author

Rafael E. Arellano
Electrical Engineer
ICT & Low-Voltage Infrastructure

LinkedIn: Rafael E. Arellano

GitHub: rafaelarellano
