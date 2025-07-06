# Comfy UI Img 2 Img Workflow using Flux.1 Fill [Dev]

Note: Relevant code files for my readers @Medium. Here's where you can access my write-up: https://medium.com/@mg.20021906

**Purpose**

A full Img-to-Img generation workflow using quantized Flux.1 Fill models. The given workflow changes the outfit of the cartoon character present in the example image.

**How to edit the Masks?**

Method 1: 

Right Click the Loaded Image and Click 'Open in Mask Editor'.

Method 2:

Simply load a Black and White Mask-Image using a new 'Load Image' node and connect it to the 'InpaintModelConditioning' node.
