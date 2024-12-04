# Tailwind CSS Gradient Distortion Bug

This repository demonstrates an uncommon bug encountered while using Tailwind CSS gradients. The gradient background doesn't render correctly, displaying a distorted or incomplete appearance.

## Bug Description

The gradient might not completely fill the background of an element, leading to unexpected color breaks or missing portions of the gradient.  This issue seems specific to certain gradient combinations and might be related to the interplay of Tailwind's utility classes and CSS gradient rendering engine.

## Reproduction Steps

1. Clone this repository.
2. Open `index.html` in a web browser.
3. Observe the distorted gradient in the example div.

## Solution

The solution involves ensuring proper dimensions and applying the gradient to an element that has a defined size.  The problem is often caused when using a class without explicitly setting the dimensions for the parent container.