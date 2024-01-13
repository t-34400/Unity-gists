# Meta Quest Dynamic Toggle Group Basis Prefab

## Overview

The "MetaDynamicToggleGroup" prefab is designed to manage a dynamic toggle group specifically optimized for Meta Quest. 
It allows for the creation and management of dynamic toggles based on the provided data source. 
Follow the instructions below to integrate this prefab into your Meta Quest project.

## Usage

1. **Import the Package:**
   - Import the provided package into your Unity project.

2. **Implement ToggleGroupDataProviderBase:**
   - Implement the abstract class `ToggleGroupDataProviderBase` to provide data for the dynamic toggles. You can either:
     - Create a new ScriptableObject that inherits from `ToggleGroupDataProviderBase`, implement it, and generate the necessary asset.
     - Use the existing `ScriptableObjects/ToggleGroupDataProvider` provided in the package.

3. **Add Meta Dynamic Toggle Group to Scene:**
   - Locate the prefab at `Prefabs/MetaDynamicToggleGroup`.
   - Drag and drop the "MetaDynamicToggleGroup" prefab into your scene.
   - In the inspector, attach the implemented `ToggleGroupDataProviderBase` to the `ToggleGroupDataProvider` field.

## License
MIT License
