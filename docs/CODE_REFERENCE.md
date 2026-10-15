# Code and artifact reference

[Overview](../README.md) · [Walkthrough](PROJECT_GUIDE.md) · [Development guide](DEVELOPMENT.md)

This reference describes the files on this branch. Function names are navigation aids; the walkthrough explains how their inputs, state, and outputs fit together.

## Repository artifacts

| File | Responsibility |
| --- | --- |
| [car_rental.rp](../car_rental.rp) | Original Axure native project; open a working copy in a compatible Axure RP editor. |
| [.gitattributes](../.gitattributes) | Mark `.rp` files as binary so Git does not treat the project as line-oriented text. |
| [.gitignore](../.gitignore) | Exclude generated exports, temporary files, and local backups. |

## What can be inspected

Axure pages, widgets, variables, interactions, and reusable components live inside the native project. A compatible editor is required to inspect them reliably. Their exact names, counts, and interaction rules have not been verified in this environment, so this reference does not invent a class list or page map.

A generated HTML preview is a derived review artifact. It is not a backend application, database, payment integration, or proof of implemented business operations. Follow the walkthrough to record page names, verify interactions, and generate a preview locally. Preserve the native project and review the editor's compatibility prompts before saving any conversion.

## Validation boundary

The documentation and binary Git handling were checked. No Axure rendering, internal widget inspection, or interactive acceptance test was performed. This phase leaves the `.rp` bytes unchanged.
