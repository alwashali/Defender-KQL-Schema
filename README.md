# Defender-KQL-Schema
Microsoft Defender Advanced Hunting KQL Schema

- **Schema.json** contains the default schema from MS 
- **minimized_schema.json** contains smaller version by removing some columns
- **micro_schema.json** contains table name and column names


To minify the schema execute

`jq -c . < schema.json`