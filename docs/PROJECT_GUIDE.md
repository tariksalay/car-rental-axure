# Car Rental Management: Axure Prototype: project walkthrough

[Overview](../README.md) · [Code reference](CODE_REFERENCE.md) · [Development guide](DEVELOPMENT.md)

## The source of truth

[car_rental.rp](../car_rental.rp) is the editable native document. There are no separate application source modules, controllers, database migrations, or browser-runtime files checked in alongside it. Any pages, widgets, or interactions are stored within the native file rather than represented as ordinary repository folders.

The earlier project overview described a multi-office car-rental workflow. That is historical design context, not evidence that every workflow is implemented or that a database is connected.

## Repository map

| Path | Role |
| --- | --- |
| [car_rental.rp](../car_rental.rp) | Original native design artifact; no edits were made to it |
| [.gitattributes](../.gitattributes) | Marks `.rp` documents as binary rather than text-mergeable source |
| [.gitignore](../.gitignore) | Excludes generated exports, backups, and local OS artifacts |
| `exports/` | Recommended local preview destination, not a tracked deployed website |
| `backups/` | Recommended local backup destination |

## How to inspect internal objects accurately

Use a compatible Axure installation to build an inventory from the actual document. Start with its page list and identify each page’s purpose. For each page, inspect the visible components and their interactions, then preview the relevant states. Record page names and behavior as they appear in the file rather than inventing names from the project title.

This documentation does not claim a verified inventory of pages, widget IDs, dynamic states, interactions, or navigation links. The native file’s proprietary structure could not be decoded reliably in this environment; generated application diagrams would otherwise risk presenting assumed features as implemented ones.

## An editable document is different from a service

A native prototype describes an interface and simulated interactions. An exported preview is a derived browsing artifact. Neither establishes server-side booking persistence, inventory consistency, customer authentication, payments, real office integration, or SQL connectivity. The repository contains no implementation of those services that can be verified from separate application source.

## A useful review session

Open the document, record the actual start page, and follow a proposed user journey using only interactions that are present. Note which transitions work, which states are static examples, and which behaviors are only explanatory content. Export to a local preview folder and compare it with the native document. Keep intentional screenshots or a walkthrough in a tracked documentation folder if they are later produced; avoid committing bulk generated previews by default.

The file was not opened or visually tested in Axure during this pass. Its native bytes remain unchanged, and no generic mockup is substituted for the original. The [development guide](DEVELOPMENT.md) describes the working/export conventions; the [artifact reference](CODE_REFERENCE.md) makes the verified and unverified boundaries explicit.
