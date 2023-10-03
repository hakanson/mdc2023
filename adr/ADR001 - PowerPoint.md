# ADR001 - Use PowerPoint for presentations

## Status

Adopted

## Decision

Natively use PowerPoint to create architecture diagrams used in presentations.

## Context

AWS Solutions Architects deliver lots of customer facing presentations, many of which combine slides from existing presentations.  These presentations are expected to meet the high bar for quality.

## Options Considered

Natively draw in PowerPoint

- `+` PowerPoint is an official source of both light and dark AWS icons
- `+` Easy to reuse across presentations
- `+` Supports advanced features such as animation

Draw in Draw.IO and paste image into PowerPoint

- `+` Draw.IO has more features as a drawing tool
- `-` Any updates require access to original `.drawio` file

## Consequences

`-` Drawing tools and diagrams-as-code are needed for other use cases.

## Advice

None provided
