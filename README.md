# TYPO3 TCA Snippets Extension

TCA Snippets for [TYPO3 TCA](https://docs.typo3.org/m/typo3/reference-tca/main/en-us/Index.html) in VSCode and VSCodium.<br>
If you want to contribute your own snippets, [create a Pull Request via GitHub](https://github.com/pagea-dev/typo3tca-snippets/pulls)<br>
If you have problems or ideas, [open an Issue via GitHub](https://github.com/pagea-dev/typo3tca-snippets/issues)<br>
You can find the source code on [GitHub](https://github.com/pagea-dev/typo3tca-snippets)

Download for VSCode [from the Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=pagea-dev.typo3tca-snippets)<br>
Download for VSCodium [from Open-VSX.org](https://open-vsx.org/extension/pagea-dev/typo3tca-snippets)

## Features

All snippets are compatible with TYPO3 13 and 14.

### Structure

| Prefix | Description |
|---|---|
| `tcafull` | Complete TCA base structure for a new table |
| `tcaoverride` | TCA override for existing table (e.g. tt_content) |
| `tcactrl` | ctrl block |
| `tcatypes` | types block with showitem and palette syntax |
| `tcapalettes` | palettes definition |
| `tcacolumns` | Empty columns scaffold |
| `tcacolumnwrapper` | Column definition with label, exclude, l10n_mode and config placeholder |

### Text & Input

| Prefix | Description |
|---|---|
| `tcainput` | Text input field |
| `tcanumber` | Number field |
| `tcanumberslider` | Number field with slider |
| `tcadatetime` | Datetime field (date, time, datetime, timesec) |
| `tcaemail` | Email field |
| `tcapassword` | Password field |
| `tcatextarea` | Textarea field |
| `tcarte` | Rich Text Editor field |
| `tcaslug` | Slug field |
| `tcacolor` | Color picker field |
| `tcalink` | Link field |
| `tcajson` | JSON editor field |
| `tcauuid` | UUID field |
| `tcanone` | None field (read-only display) |
| `tcapassthrough` | Passthrough field (invisible, stores data without UI) |
| `tcauser` | User field with custom renderType |
| `tcaflexform` | FlexForm field |

### Checkboxes

| Prefix | Description |
|---|---|
| `tcacheck` | Checkbox field with items |
| `tcacheckcols` | Checkbox field with multiple columns |
| `tcacheckcolsinline` | Checkbox field with inline columns |
| `tcachecktoggle` | Checkbox toggle |
| `tcachecklabeledtoggle` | Checkbox labeled toggle |

### Select & Relations

| Prefix | Description |
|---|---|
| `tcaselectsingle` | Single select field (static items) |
| `tcaselectmulti` | Multi-select side-by-side field (static items) |
| `tcaselectside` | Multi-select side-by-side field (DB relation) |
| `tcaselectmm` | Select field with MM (many-to-many) relation |
| `tcaselecttree` | Select tree field |
| `tcaradio` | Radio buttons field |
| `tcacategory` | Category tree field |
| `tcafalimage` | FAL image field |
| `tcafile` | FAL file field (configurable allowed types) |
| `tcagroup` | Group field (DB relation) |
| `tcainline` | Inline (IRRE) field |

### Standard / System Fields

| Prefix | Description |
|---|---|
| `tcahidden` | Standard hidden field |
| `tcastarttime` | Standard starttime field |
| `tcaendtime` | Standard endtime field |
| `tcafegroup` | Standard fe_group field |
| `tcasyscat` | sys_category relation field |

### Misc

| Prefix | Description |
|---|---|
| `tcadisplaycond` | Display condition |
| `tcal10nmode` | l10n_mode for translation handling |
| `tcasearchfields` | searchFields entry for ctrl |
| `tcasecurity` | security array for ctrl |
| `tcauniversal` | Field with config inherited from tt_content |

## Requirements

- TYPO3 13 or higher
- VSCode `^1.90.0` or VSCodium equivalent

## Installation

### Via Open VSX (VSCodium)

Search for `TYPO3 TCA Snippets` in the Extensions tab.

### Via Marketplace (VSCode)

Search for `TYPO3 TCA Snippets` in the Extensions tab or install via:

```
ext install pagea-dev.typo3tca-snippets
```

### Manual (.vsix)

Download the latest `.vsix` from the [Releases](https://github.com/pagea-dev/typo3tca-snippets/releases) page and install via:

```
Extensions → ··· → Install from VSIX...
```

## Contributing

Pull requests are welcome. For larger changes please open an issue first.

1. Fork the repository
2. Create your branch: `git checkout -b feat/my-snippet`
3. Commit your changes: `git commit -m 'feat: add tcainput snippet'`
4. Push and open a Pull Request

## License

[MIT](LICENSE)