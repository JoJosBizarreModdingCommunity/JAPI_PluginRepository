# JAPI Plugin Repository

Metadata + binaries for JAPI plugins!

## How to add my plugin?

1. Fork this repository
2. Add your plugin binaries to `plugins/` (notice: the binary should be named after the plugin's `guid` and have the `.dll` extension)
3. Add your plugin metadata to `plugins.json` (notice: the `url` should be a direct link to the binary in ***this*** repository)
4. Create a pull request
5. Wait for approval :)

## Example Plugin metadata

```json
{
    "name": "CPK Mod Loader",
    "guid": "CPKModLoader",
    "author": "Kapilarny",
    "version": "1.0.0",
    "description": "Allows for the loadage of .cpk mods!",
    "url": "https://github.com/Kapilarny/JAPI/raw/refs/heads/3_1_0_rewrite/libJAPIPlugin.dll",
    "source_url": "https://github.com/Kapilarny/JAPI/",
    "lazy_load": false,
    "dependencies": []
}
```
