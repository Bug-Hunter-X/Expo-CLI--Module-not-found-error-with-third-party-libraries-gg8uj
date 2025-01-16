# Expo CLI: Module Not Found Error with Third-Party Libraries

This repository demonstrates a common issue in Expo projects: encountering 'Module not found' errors when using libraries that require native modules.  The problem often stems from incorrect installation or linking of these libraries within the Expo managed workflow.

## Problem

When using a library like `react-native-uncommon-lib` (a hypothetical example) that relies on native code, you might receive errors such as 'Module not found' or similar messages, even if you think the library is correctly installed.

## Solution

This issue is usually resolved by ensuring the library is correctly installed and, if necessary, linked. Expo's managed workflow has some limitations compared to bare React Native projects.  The solution may involve using an Expo-compatible library or properly configuring a native module if one is required.  Check the library's documentation for Expo-specific instructions. 

The included `bug.js` and `bugSolution.js` files illustrate the problem and its solution.