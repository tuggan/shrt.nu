---
title: "Patches"
date: 2019-01-28T10:07:16+01:00
draft: true
description: "General patches"

type: "page"

creatordisplayname: "Dennis Vesterlund"
creatoremail: "dennisvesterlund@gmail.com"
lastmodifierdisplayname: "Dennis Vesterlund"
lastmodifieremail: "dennisvesterlund@gmail.com"

---

# Patches

Sometimes i create patches for existing application, this is where i leave them.

# Patch generation
```
git format-patch --stdout <SHORTHASH> > program-function-YYYYMMDD-SHORTHASH.diff
```
- program: Program is the name of the program the patch applies to.
- function: The function the patch adds.
- YYYYMMDD: Date the patch was extracted.
- SHORTHASH: Seven chars git commit that indicates what commit the patch was built from.

{{%children style="h2" description="true"%}}
