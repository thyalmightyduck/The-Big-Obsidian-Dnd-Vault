
---
copied_property: "<%* 
  // Get the file you clicked the button from
  let sourceFile = tp.config.active_file; 
  // Read its frontmatter cache
  let cache = app.metadataCache.getFileCache(sourceFile);
  // Replace 'species_select' with the exact name of your YAML property
  let propertyValue = cache?.frontmatter?.project_id || 'Default Value';
  tR += propertyValue;
%>"
---
# New Note Created via Button
This note captured the property from [[<% sourceFile.basename %>]].
