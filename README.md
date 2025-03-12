# Defender-KQL-Schema
Microsoft Defender Advanced Hunting KQL Schema

- Schema.json contains the default schema from MS 
- minimized schema.json contains smaller version by removing some columns


To minify the schema execute

`jq -c . < schema.json`