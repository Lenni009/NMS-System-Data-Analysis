## Summary

This script reads JSON files as returned by the NMS API, then converts that data
into CSV files.

## Prerequisites

- [Deno](https://deno.land/manual@v1.32.3/getting_started/installation)

## Usage

The JSON files should be in subfolders of the `data` folder. This Script is
intended to analyse multiple regions simultaneously. Each region will have its
own output csv, and there will also be one global csv. The regions are
represented by the folders in `data`.

CLI command to run:

```
deno run --allow-read --allow-write main.js
```