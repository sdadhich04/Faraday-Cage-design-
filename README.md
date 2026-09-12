# Faraday Cage CAD Design

This repository contains CAD export files for a two-part Faraday cage design.

## Contents

- `Part Studio 1 (1).zip` - STEP AP242 exports for `Part 1` and `Part 2`.
- `Part Studio 1.zip` - STL exports for `Part 1` and `Part 2`.

The STEP files identify Onshape by PTC as the originating CAD system. The STEP
exports use SI metre units; the STL coordinates appear to be in millimetres.

## Design Notes

- The repository contains design geometry exports only.
- No source CAD workspace file, material specification, assembly instructions,
  simulation output, or test/validation data is included in this checkout.
- Derived bounding boxes from the exported geometry:
  - STEP `Part 1`: 190 mm x 190 mm x 200 mm.
  - STEP `Part 2`: 200 mm x 200 mm x 330 mm.
  - STL `Part 1`: 190 x 190 x 200 in the STL coordinate units.
  - STL `Part 2`: 200 x 190 x 80 in the STL coordinate units.

## How to Use

Download and extract the ZIP files, then open the STEP files in a CAD tool or
the STL files in a slicer or mesh viewer.

## Credits

The Git history in this checkout lists commits by `sdadhich04 <sdadhich@uw.edu>`.
