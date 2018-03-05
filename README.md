# blender-scripts
Miscellaneous python scripts for Blender (just useful operators for now)

## Installation

Download the latest zip from [Releases](https://github.com/pezcode/blender-scripts/releases) and import it into Blender (*File* > *User Preferences* > *Add-ons* > *Install Add-on from File...*). Check the box next to the name to enable it.
If you want it to automatically load with Blender, click *Save User Settings*.

You can use:
```bash
python make_zip.py
```
to create the zip file from source if you made changes.

## Operators

### object.batch_rename

Rename and number objects, sorted by:
  - x/y/z location
  - size
  - distance from center
  - randomly

### object.bounds_mesh

Create a mesh that represents the bounding box(es) of the selected object(s). Useful for boolean operations.

### object.copy_custom_properties

Copy custom properties from the active object to all selected objects, including (soft) min/max. Keeps previously defined properties.
