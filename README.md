# Railroader API Documentation

**Comprehensive API reference for Railroader game modding**

This repository contains auto-generated documentation extracted from Railroader's decompiled C# source code, providing a complete API reference for creating mods using Unity Mod Manager (UMM).

## 🎯 Purpose

This documentation helps modders:
- Discover available classes, methods, and properties in Railroader
- Understand game systems and their APIs
- Find the right hooks for Harmony patching
- Reference type signatures for mod development
- Navigate the codebase structure by namespace

## 📚 Documentation Structure

- **[API Reference](docs/api/)** - Auto-generated from decompiled source code
  - Browse by namespace (Model, Track, Game, UI, etc.)
  - Complete type definitions with methods and properties
  - Inheritance and interface information
- **[Guides](docs/guides/)** - Modding tutorials and best practices
- **[Examples](docs/examples/)** - Code examples and patterns

## 🔧 Key Namespaces

| Namespace | Description |
|-----------|-------------|
| **Model** | Core game entities (Cars, Locomotives, Definitions) |
| **Track** | Track system (Location, Segments, Switches, Signals) |
| **Game** | Game state, events, and lifecycle management |
| **UI** | User interface components and windows |
| **RollingStock** | Train car components and controls |
| **Network** | Multiplayer and networking |
| **Audio** | Sound system and audio playback |
| **AssetPack.Runtime** | Asset loading and management |

## 🚀 Quick Start for Modders

### Finding What You Need

1. **Browse by Namespace:** Navigate to [docs/api/](docs/api/) and explore namespaces
2. **Search for Types:** Use GitHub's search or your browser's find function
3. **Check Inheritance:** Look at class declarations to understand relationships
4. **Use with Context7:** This repo is indexed by Context7 for AI-assisted coding

### Common Modding Patterns

**Subscribing to Game Events:**
```csharp
using GalaSoft.MvvmLight.Messaging;
using Game.Events;

Messenger.Default.Register<MapDidLoadEvent>(this, OnMapDidLoad);
```

**Working with Cars:**
```csharp
using Model;

Car myCar = ...; // Get car reference
var location = myCar.location; // Track.Location
var speed = myCar.velocity; // Current velocity
```

**Harmony Patching:**
```csharp
using HarmonyLib;

[HarmonyPatch(typeof(TargetClass), "MethodName")]
public static class MyPatch {
    static bool Prefix() {
        // Your code
        return true; // false = skip original
    }
}
```

## 📖 Related Resources

- **[Unity Mod Manager](https://www.nexusmods.com/site/mods/21)** - Mod loader for Railroader
- **[Harmony Documentation](https://harmony.pardeike.net/)** - Runtime patching library
- **[Modding Template](https://github.com/...)** - Starter template for new mods
- **[Railroader Discord](https://discord.gg/railroader)** - Community discussion

## ⚙️ Documentation Generation

This documentation is auto-generated using a PowerShell script that:
- Parses decompiled C# source files
- Extracts classes, methods, properties, and fields
- Organizes by namespace
- Generates Markdown documentation
- Tracks game version changes

**Game Version:** 2025.1.0b
**Last Generated:** Check `.generation-metadata.json`

### Updating Documentation

When Railroader releases a new version:
1. Decompile new game files using AssetRipper
2. Run the documentation generator script
3. Review changes and commit
4. Context7 automatically reindexes

## 🤝 Contributing

### Documentation Issues

Found an error or have a suggestion?
- Open an issue describing the problem
- For auto-generated content, note that regeneration may overwrite manual fixes
- Consider contributing to guides and examples instead

### Adding Guides and Examples

Contributions to `docs/guides/` and `docs/examples/` are welcome!
1. Fork this repository
2. Add your Markdown files
3. Follow existing formatting conventions
4. Submit a pull request

## ⚠️ Disclaimer

This documentation is derived from decompiled Railroader source code for modding purposes only. All rights to Railroader belong to their respective owners.

**This is unofficial documentation created by the modding community.**

## 📜 License

Documentation content: CC BY-SA 4.0
Railroader game code: Copyright © Altfuture/Giraffe Lab LLC

---

**Generated with Love by the Railroader Modding Community** 💙🚂

*Powered by [Claude Code](https://claude.com/claude-code) | [Task Master AI](https://www.npmjs.com/package/task-master-ai)*
