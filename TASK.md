# Task

Your objective is to DESIGN the part, not explain how to design it.

The repository contains a STEP model of the original BoboVR B100 battery.

Use this model as a dimensional reference and create a compatible accessory.

## Required output

Generate:

- OpenSCAD source
- STEP
- STL

The generated files must be placed into an `/output` directory.

---

## The accessory

Design a magnetic protective cover for the battery contact side.

Purpose:

- protect electrical contacts
- prevent accidental short circuits
- prevent damage during transport
- remain attached inside a backpack

---

## Requirements

The cover must:

- fit the battery correctly
- require no supports
- print on a standard FDM printer
- use minimal material
- have rounded edges
- include a thumb tab
- include two magnet pockets

Magnets:

10 mm diameter

3 mm thickness

General clearance:

0.25 mm

Lip height:

2 mm

Top thickness:

3 mm

---

## Design process

Use the STEP file to determine:

- overall dimensions
- contact geometry
- battery perimeter
- magnet locations

The generated geometry should reference the battery dimensions rather than using manually typed measurements whenever practical.

---

## Constraints

Do NOT redesign the battery.

Do NOT modify the battery model.

Create only the accessory.

---

## Deliverables

/output

    ContactCover.scad

    ContactCover.step

    ContactCover.stl

---

## Success criteria

The part should:

- fit without excessive force
- not wobble
- protect all contacts
- print without supports
- be aesthetically clean

If any ambiguity exists, choose the solution that maximizes reliability and printability.
