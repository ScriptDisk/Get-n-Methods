# Get _n_ Methods README

## Overview

Get _n_ Methods is a utility tool for .NET developers, specifically designed to analyze C# source files and generate a list of methods using Roslyn.

## Installation

The installer for Get _n_ Methods can be found at the following URL: [Get n Methods Installer](https://github.com/ScriptDisk/Get-n-Methods/tree/main/Installer)

## How It Works

1. **Read File**: Asynchronously reads the specified C# file.
2. **Parse Syntax**: Uses Roslyn to parse the file into a syntax tree.
3. **Extract Methods**: Identifies and extracts details of each method.
4. **Generate Report**: Compiles a timestamped and detailed report of all methods, available as a downloadable `.txt` file.
