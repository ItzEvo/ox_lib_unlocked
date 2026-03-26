# ox_lib

Fork-friendly editable RedM build based on the public LGPL ox_lib project.

- Resource name: `ox_lib`
- Target: RedM / RSG-compatible environments
- Web source included in `web/src`
- Built UI included in `web/build`
- Original upstream credits and LGPL license retained

## Notes

- This fork changes the runtime/import/export resource name from `ox_lib` to `ox_lib`.
- Resources importing this fork should use `@ox_lib/init.lua` and `exports.ox_lib`.
- `fxmanifest.lua` is RedM-only and includes the required `rdr3_warning` line.

## Frontend customization

Edit:
- `web/src/theme/*`
- `web/src/features/*`
- `web/build/assets/*` for direct live asset patching

## License

This fork remains under the original LGPL-3.0-or-later terms. See `LICENSE`.


> RedM drop-in editable build prepared by ItzEvo. Resource name remains `ox_lib` for compatibility.

## Custom Theme
Edit `web/build/custom_theme.css` for live changes or `web/src/styles/custom_theme.css` for source-side changes.


## Drag-and-drop package
This package includes:
- runtime Lua source
- `web/src` source files
- `web/build` compiled UI files

`web/build` is included so the resource works immediately when dropped into a server.
Edit `web/build/custom_theme.css` for live UI changes.
