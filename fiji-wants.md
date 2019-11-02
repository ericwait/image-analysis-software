---
title: Ideal Fiji Improvements
date: November 1, 2019
author:
	- Eric Wait
	- Blair Rosetti
fontfamily: merriweather
fontfamilyoptions: sfdefault
---

Many of the Improvements needed are also stated in [^rueden].

## Concerns

- Consistency
	- Many plugins open up their own interface. 
		- Namely for file reading purposes.
	- Not all plugins are scriptable, making it difficult to make automated pipelines.
	- Unpredictable behavior of plugins (need standards for API)
	- Disorganized menu layout and UI
	- **Undo**
- Inability to read and process large 5-D datasets.
	- No virtual stack paradigm for new data types (_e.g._ KLB files)
- Complicated Updater
	- Confusing error messages
	- Intrusive
	- Updates sites are hidden
- Discovering new methods is difficult
- Ability to run macros / pipelines headless is non-trivial
- Inconsistent of maintenance of plugins
- Writing macros in other languages lack support for external package/libraries
- Large barrier to entry for plugin writers

[^rueden]: Rueden, C. T., Schindelin, J., Hiner, M. C., DeZonia, B. E., Walter, A. E., Arena, E. T., & Eliceiri, K. W. (2017). ImageJ2: ImageJ for the next generation of scientific image data. BMC Bioinformatics, 18(1), 1–26. https://doi.org/10.1186/s12859-017-1934-z