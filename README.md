# 3D Slicer Wrist Segmentation Example

This repository demonstrates semi-automatic segmentation of wrist bones using 3D Slicer on a dynamic MRI dataset.

## Dataset

Public dataset:
https://data.mendeley.com/datasets/9kx5xp7h6d/2

The dataset includes:

- High-resolution wrist MRI
- Dynamic wrist motion sequences
- 40 frames per subject
- NIfTI format

## Segmentation Workflow (3D Slicer)

Semi-automatic segmentation was performed using 3D Slicer Segment Editor.

Tools used:
- Grow from Seeds
- Paint
- Smoothing
- Manual refinement

Segmented structures:

- Radius
- Capitate
- Scaphoid
- Lunate

## Workflow

1. Load high-resolution reference frame
2. Apply Grow-from-Seeds segmentation
3. Refine segmentation manually
4. Visualize in 3D
5. Export segmentation masks

## Example

Example segmentation shown below.

## Purpose

This example demonstrates:

- 3D Slicer segmentation workflow
- Medical image annotation
- Multi-bone wrist segmentation
- Dynamic MRI analysis# dynamic-wrist-segmentation
Semi-automatic wrist bone segmentation in 3D Slicer using dynamic MRI data from a public dataset.
