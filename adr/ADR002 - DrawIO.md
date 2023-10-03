# ADR002 - Use DrawIO (desktop) for documentation

## Status

Adopted

## Decision

Use DrawIO (desktop) to create most architecture diagrams used in documentation.

## Context

Diagram images are included in project documentation, often created in markdown format.

## Options Considered

Draw in Draw.IO and export as PNG

- `+` Draw.IO has more features as a drawing tool
- `+` Draw.IO has multiple options for exporting
- `-` Any updates require access to original `.drawio` file

Draw in PowerPoint and export as PNG

- `-` PowerPoint export workflow requires intermediate paste using Word

PlantUML

- `-` Auto-layout distracting and hard to tweak

## Consequences

`-` Diagrams-as-code tools needed for some images types

## Advice

None provided
