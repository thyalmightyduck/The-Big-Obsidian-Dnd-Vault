---
<%*
  // 1. Fetch the source file and its metadata cache
  let sourceFile = tp.config.active_file;
  let cache = app.metadataCache.getFileCache(sourceFile);
  let fm = cache?.frontmatter;

  // 2. Extract your properties (replace the names on the right with your actual YAML keys)
  let propA = fm?.spell_select_cantrips || "No Project ID";
  let propB = fm?.species_select || "No Status";
  let propC = fm?.class_selector || "No Client";

  // 3. Output them cleanly as individual YAML lines
  tR += `spell_select_cantrips: "${propA}"\n`;
  tR += `species_select: "${propB}"\n`;
  tR += `client: "${propC}"\n`;
-%>
---






