# CAD Coding Guidelines

## General

The generated CAD should be fully parametric.

Avoid hardcoded magic numbers whenever possible.

---

## Parameters

Expose the following parameters:

clearance

lip_height

top_thickness

magnet_diameter

magnet_height

tab_length

tab_height

fillet_radius

---

## OpenSCAD

Write readable code.

Separate:

- parameters
- helper modules
- final assembly

Avoid duplicated geometry.

---

## Geometry

Prefer constructive solid geometry (CSG).

Avoid meshes.

Avoid imported STL unless absolutely necessary.

Use the STEP model as reference only.

---

## Printing

Target:

0.4 mm nozzle

0.20 mm layers

PLA

PETG

No supports.

Flat orientation.

---

## Magnet pockets

Provide either:

slight press fit

or

light glue fit

Pocket depth should leave the magnet flush.

---

## Tolerances

Target:

0.25 mm clearance

Never use zero-clearance mating surfaces.

---

## Deliverables

Every exported model should be manifold.

No self-intersections.

No inverted faces.

STL should be printable without repair.

---

## Preferred workflow

STEP

↓

Parametric CAD

↓

OpenSCAD

↓

STEP export

↓

STL export

Do not generate STL directly from meshes.
