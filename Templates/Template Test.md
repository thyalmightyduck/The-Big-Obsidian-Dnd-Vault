
---
Species: "<%* 
  let sourceFile = tp.config.active_file; 
  let cache = app.metadataCache.getFileCache(sourceFile);
  let propertyValue = cache?.frontmatter?.species_select || 'Default Value';
  tR += propertyValue;
%>"
---

