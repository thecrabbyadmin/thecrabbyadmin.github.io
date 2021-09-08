---
layout: tag
title:  "Get Date Information"
date:   2021-02-01 20:48:41 -0600
categories: jekyll update
---

A quick easy way to get date information is using the Get-Date PowerShell cmdlet.

When you use the Get-Date cmdlet at a PowerShell console it returns the current date and time.
```
PS C:\Users\Greg> get-date
Tuesday, September 7, 2021 9:51:08 PM
```

Now you can use a method to add or subtract days.

```
PS C:\Users\Greg> (get-date).AddDays(-5)
Thursday, September 2, 2021 10:07:30 PM
```

