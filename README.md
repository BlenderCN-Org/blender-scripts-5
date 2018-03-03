# blender-scripts
Miscellaneous python scripts for Blender

## Installation

To install all scripts (currently just operators), create a zip file

```bash
python make_zip.py
```

and import it into Blender (*File* > *User Preferences* > *Add-ons* > *Install Add-on from File...*). Check the box next to the name to enable it.
If you want it to automatically load with Blender, click *Save User Settings*.

## Scripts

### batch_rename

Rename and number objects, sorted by:
  - x/y/z location
  - size
  - distance from center
  - randomly

### bounds_mesh

Create a mesh that represents the bounding box(es) of the selected object(s). Useful for boolean operations.
