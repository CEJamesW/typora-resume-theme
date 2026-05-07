# Typora Resume Theme

A custom Typora theme set for resume and document writing.

## Files

- `resume.css`: light resume theme.
- `resume-night.css`: dark resume theme.
- `night/`: dark-mode helper styles imported by `resume-night.css`.

## Install

1. Download or clone this repository.
2. Copy `resume.css`, `resume-night.css`, and the `night` folder into Typora's theme folder.
3. Restart Typora.
4. Select `resume` or `resume-night` from Typora's theme menu.

On Windows, Typora's theme folder is usually:

```text
%APPDATA%\Typora\themes
```

## Notes

The CSS files include local font fallbacks for Chinese and monospace text. They also reference `fluent/fontawesome-webfont.*`, but that folder was not present in the local Typora theme directory when this repository was created, so it is not included here.