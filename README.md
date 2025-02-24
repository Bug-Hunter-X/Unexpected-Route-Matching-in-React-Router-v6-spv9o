# React Router v6 Unexpected Route Matching Issue

This repository demonstrates an unexpected route matching behavior in React Router v6.  A seemingly simple route definition leads to incorrect rendering. The issue is subtle and might be difficult to spot for developers unfamiliar with the intricacies of React Router's route matching algorithm.

## Problem Description

The `Contact` component is unexpectedly rendered even when the path doesn't exactly match. This happens due to an ambiguous or poorly defined route that may cause unintended matching.