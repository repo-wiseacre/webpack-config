# Unpublished 

- Added lots of code comments
- Added '~/' src alias for imports
- Now affixes 'bundle' to bundle file names
- Now includes hash in chunk file names
- Fix now resolves .scss and .css modules
- Turned on 'strictExportPresence'
- Disable 'require.ensure' as it's not a standard language feature.
- NODE_ENV now equals 'development' in dev mode
- Changed default dev tool to 'cheap-module-source-map' in favour for source files in browser dev tools
- Added NamedModulesPlugin in dev mode for performance testing