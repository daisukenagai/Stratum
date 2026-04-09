# AGENTS.md

## Project

Donut Hole

Experimental one-page website for a designer collective.

## Purpose

This site is meant to express a playful and quiet resistance to hyper-efficiency in the AI era.

It should value:

- emptiness
- margins
- uselessness
- ambiguity
- beauty without over-explaining itself

The site should also subtly demonstrate a Design Engineer / Design Technologist approach through implementation quality and interaction design.

## Core Concept

Donut Hole is a place for doing things without a productive purpose.

It is not a portfolio piece driven by performance, growth, or optimization.
It is a small visual and interactive expression of meaningless but valuable time.

## Creative Direction

- Quiet
- Minimal
- Outline-based
- Light gray / white dominant
- Thin strokes
- No loud visuals
- No overly polished corporate feel
- No excessive motion for its own sake

The visual motif is not a literal donut, but the impression of a donut-like void.

## Graphic Specification

The background graphic should:

- sit on a very light gray background
- consist of multiple thin elliptical outline lines
- be slightly distorted with p5.js noise
- move slowly as if breathing
- change distortion amount gradually based on scroll
- react to mouse interaction by denting inward near the cursor
- remain subtle and atmospheric rather than dominant

## Technical Direction

- Built as a one-page site under an existing Astro project
- Prefer simple implementation over architectural complexity
- Use p5.js for generative graphics
- Use Lenis for scroll behavior
- Avoid introducing more libraries unless clearly necessary
- Prefer CSS and native browser capabilities when possible
- GSAP is optional and should only be added if a clear need appears

## Constraints

- Completion is more important than sophistication
- Avoid large-scale refactors
- Avoid heavy 3D or shader-based approaches
- Avoid over-engineering
- Keep dependencies minimal
- Keep code understandable and editable by a solo creator

## Definition of Done

A first version is done when:

- the page exists and is routed correctly in Astro
- the p5.js background renders properly
- scroll affects distortion amount
- mouse interaction causes local denting
- the text and background coexist beautifully
- the site feels calm, strange, and intentional
- performance is acceptable on modern desktop and mobile browsers

## Working Style

When making changes:

- preserve the minimal concept
- keep edits small and focused
- explain major implementation decisions briefly
- do not add decorative features without conceptual value
- prefer subtlety over spectacle
