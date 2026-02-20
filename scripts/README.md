# Scripts Overview
All scripts used in the exploration or analysis of [Project Name].

Scripts prefixed with a number (e.g. `00_`, `01_`) follow a sequential workflow 
and depend on prior steps. Unnumbered scripts can generally be run independently.

*Last updated: [Name, Date]*

## Folders
- **analysis** - finalized scripts and analyses
- **exploratory** - a range of useful to just plain incomplete products for 
  exploring data. Final scripts used in analyses should be moved to the analysis subfolder.

## Files
Scripts in the root `scripts/` folder are shared resources used across analysis 
and exploratory workflows. This may include data download, reformatting, or helper 
functions used by multiple scripts.

- `00_[name].R` - [description]
- `functions_[topic].R` - helper functions for [topic]. Formatted for pulling 
  into an R package if needed in the future.
