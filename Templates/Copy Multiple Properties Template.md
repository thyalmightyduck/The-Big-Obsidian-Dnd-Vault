---
<%*
  // 1. Fetch the source file and its metadata cache
  let sourceFile = tp.config.active_file;
  let cache = app.metadataCache.getFileCache(sourceFile);
  let fm = cache?.frontmatter;

  // 2. Extract your properties (replace the names on the right with your actual YAML keys)
  let propA = fm?.species_select || "No Project ID";
  let propB = fm?.class_selector || "No Status";
  let propC = fm?.background_selector || "No Client";

  // 3. Output them cleanly as individual YAML lines
  tR += `species_select: "${propA}"\n`;
  tR += `class_selector: "${propB}"\n`;
  tR += `background_selector: "${propC}"\n`;
-%>
---

# Character Info:
Species: `= this.species_select`
Class: `= this.class_selector`
Background: `= this.background_selector`




