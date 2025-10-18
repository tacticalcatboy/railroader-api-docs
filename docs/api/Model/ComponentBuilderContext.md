# ComponentBuilderContext Struct

**Namespace:** `Model`
**Source:** `ComponentBuilderContext.cs`

## Declaration

```csharp
public readonly struct ComponentBuilderContext : IDefinitionReferenceResolver, IPrefabInstantiator
```

## Properties

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `CarColorController` | `CarColorController` | public | - |

## Methods

### Resolve

```csharp
public Material Resolve(MaterialReference materialReference)
```

## Fields

| Name | Type | Access | Modifiers |
|------|------|--------|-----------|
| `_animationMap` | `AnimationMap` | private | `readonly` |
| `_materialMap` | `MaterialMap` | private | `readonly` |
| `_prefabInstantiator` | `IPrefabInstantiator` | private | `readonly` |

