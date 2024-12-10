# Tailwind CSS Gradient Silent Error

This repository demonstrates a subtle bug in Tailwind CSS related to gradient usage.  If you use an invalid class name within a gradient definition, no error is thrown, but the gradient will not render correctly.  This can be difficult to debug.

## Bug

The bug is caused by using an invalid Tailwind class name within a gradient definition.  Tailwind doesn't explicitly report an error, so the problem may go unnoticed.

## Solution

The solution involves carefully checking all class names used in gradients and utilizing tools like the Tailwind CSS IntelliSense to help prevent these errors.