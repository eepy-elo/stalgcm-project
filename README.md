# Filipino Spell Checker (LanguageTool Rules)

Rule-based Filipino spell checking rules implemented in **LanguageTool** based on **Ortograpiyang Pambansa (OP)** and **Manwal sa Masinop na Pagsulat (MMP)**.

Developed for **STALGCM – Advanced Algorithms and Complexities** at **De La Salle University**.

## Overview

This project defines **three formal spelling rules** that detect incorrect Filipino spellings with **100% precision**.
Each rule uses pattern matching and exceptions to ensure that only true spelling errors are flagged.

## Example Rule

```
CwV → CuwV
```

Example:

* kwento → kuwento

## Files

```
rules.xml        # LanguageTool rule definitions
documentation.pdf
demo.mp4
```

## Tools

* LanguageTool
* XML
* Regular Expressions
