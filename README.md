# Bounding_Box_Automation_For_SW
Solidworks CAD software is a macro software that creates a bounding box for each part and all sub-assemblies of large assembly models. This software allows you to automatically find the dimensions of parts and assemblies in x,y,z axes when creating tables such as BOQ and BOM. 

## What Does This Macro Do?

- Automatically creates Bounding Boxes for all components and subassemblies.
- Works recursively, meaning it processes subassemblies inside subassemblies.
- Skips suppressed components, so it doesn’t mess with your hidden parts.
- Handles selections properly to prevent annoying SolidWorks errors.

## What’s Inside?

```
SolidWorks-BoundingBox-Macro
 ┣ bounding_box_macro.swp  (The macro file)
 ┣ README.md               (This file)
 ┣ LICENSE (optional)       (If you want to open-source it)
 ┗ .gitignore (optional)    (For repo management)
```

## How to Use It

### Run the Macro in SolidWorks

1. Open SolidWorks.
2. Go to Tools > Macro > Run....
3. Select bounding\_box\_macro.swp.
4. Click Run and let the macro do its work.

### Add It as a Toolbar Button (Optional, But Super Handy)

Want to access it quickly? Follow these steps:

1. Open Tools > Customize....
2. Go to the Commands tab.
3. Select Macros from the left panel.
4. Drag the New Macro Button to the toolbar.
5. Select bounding\_box\_macro.swp as the macro file.
6. Give it a name and icon, and you're all set.

### What You’ll See

- The macro will go through all parts and subassemblies.
- Bounding boxes will be automatically created.
- Suppressed components will be ignored.
- Works with both top-level and nested assemblies.

## Things to Keep in Mind

- Make sure SolidWorks API is enabled before running the macro.
- If you get any errors while switching between assemblies, check if the correct selections are active.

## License

This project is licensed under the MIT License, so feel free to use, modify, and share it.

## Want to Contribute?

If you have ideas or improvements:

- Fork the repo.
- Create a new branch (feature-my-awesome-feature).
- Submit a Pull Request.

##


