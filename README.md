# BoboVR B100 Magnetic Contact Cover

## Project goal

Design a compact, 3D-printable protective cover for the contact side of the **BOBOVR B100 battery**.

The cover is intended for travel and storage. It protects the electrical contacts from accidental short circuits while remaining quick to install and remove.

The design should be printable on an FDM printer without supports.

---

# Reference files

The repository contains:

- `B100.step` — accurate 1:1 CAD model of the BoboVR B100 battery.
- `B100.stl` — original mesh version (optional).

The STEP model is the reference geometry and should be used for all measurements.

---

# Functional requirements

## Primary purpose

- Protect battery contacts during transportation.
- Prevent accidental short circuits.
- Prevent dust and dirt from reaching the contacts.
- Stay attached during transport inside a backpack or suitcase.

---

# Attachment method

The cover should be retained by:

1. Two neodymium magnets.
2. A shallow locating lip that prevents lateral movement.

The locating lip should not require excessive force during installation.

---

# Magnets

Use two standard neodymium magnets:

Diameter: 10 mm
Thickness: 3 mm

Requirements:

- magnets installed flush with the inside surface
- cylindrical pockets
- press fit preferred
- glue may be used if necessary

---

# Clearances

General clearance:

0.25 mm

If the battery geometry requires it, local clearances may be adjusted between:

0.20–0.35 mm

The cover should fit comfortably after PLA or PETG printing.

---

# Geometry

Desired characteristics:

- compact
- minimal material usage
- rounded edges
- no sharp corners
- no unnecessary decorative features

Suggested values:

Top thickness:
3 mm

Locating lip:
2 mm

Edge fillets:
1–2 mm

---

# Removal

The cover should include a small thumb tab.

Requirements:

- easy one-handed removal
- no tools required
- tab should not significantly increase overall dimensions

---

# Printing

Designed for FDM printing.

Material:

- PLA
- PETG

Requirements:

- no supports
- no bridging longer than necessary
- print flat on the build plate
- printable using a 0.4 mm nozzle

Recommended layer height:

0.20 mm

---

# Deliverables

Please generate:

- OpenSCAD source (.scad)
- STEP
- STL

---

# Optional improvements

If possible, also generate an alternative version with:

- integrated keyring hole
- integrated lanyard hole

---

# Design priorities

Priority order:

1. Reliable fit
2. Contact protection
3. Easy installation/removal
4. Compact size
5. Appearance

---

# Notes

The model should be original.

Do not copy any existing commercial design.

The provided STEP model is intended only as a dimensional reference for creating a compatible accessory.
