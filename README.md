# Google Earth Engine - Asset Management using Python

Due to the difficulties I encountered in managing assets in Google Earth Engine (GEE), I have organized a complete collection of tools to manage assets in Google Earth Engine (GEE), including copy and delete operations for images, tables, collections, and complete folder structures.

## Description

This toolkit provides optimized functions to perform common asset management operations in Google Earth Engine:

- Copy individual images, tables, and collections
- Recursively copy complete folder structures
- Delete individual or batch assets
- Delete complete structures with all their dependencies
- Migrate data between user accounts and projects
- Create backups and reorganize data structures

## Features

- **Parameterized operations**: Define your user and project paths once at the beginning
- **Recursive functions**: Handle complex structures automatically
- **Visual feedback**: Progress messages and status bars with tqdm
- **Safe by design**: Deletion code commented to prevent accidental deletions

## Prerequisites

### Google Earth Engine Account
- You must have an active account at [Google Earth Engine](https://earthengine.google.com/)
- Make sure you have adequate permissions to read and write to the asset paths you will use

## Limitations and Considerations

### GEE Quotas and Limits

- **API Limits**: GEE limits the number of operations per minute
- **Storage**: Each account has storage limits
- **Concurrent operations**: Do not perform too many operations in parallel

### Recommendations

1. **Test with small data first**: Before massive operations
2. **Make backups**: Always before deleting important data
3. **Verify permissions**: Make sure you have access to source and destination
4. **Monitor progress**: Use functions with visual feedback
5. **Patience with large volumes**: Operations may take time


### Official GEE Resources

- [Official Earth Engine Documentation](https://developers.google.com/earth-engine)
- [Asset Management Guide](https://developers.google.com/earth-engine/guides/asset_manager)
- [Community Forum](https://groups.google.com/g/google-earth-engine-developers)
- [API Reference](https://developers.google.com/earth-engine/apidocs)
