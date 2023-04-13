### v1.2 -> v1.2.1

- Compatible with Python 3.10

### v1.1 -> v1.2

- Added formatting for mutability (contributed by [@AtlasQuan])
- `InitExpr` now return the initialization code (contributed by [@AtlasQuan])
- Re-export all public symbols in the root module

### v1.0 -> v1.1

- Many minor improvements and support for MVP WASM
    - Added decoding support for MVP name section
    - Added `format_function`, for formatting whole functions
    - Improved `wasmdump` command-line tool

- Slight rework of meta info visibility
    - Renamed `_data_meta` -> `_decoder_meta`
    - Added getters `get_{meta,decoder_meta}` to `StructureData`

[@AtlasQuan]: https://github.com/AtlasQuan