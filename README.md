# DirectWrite Font Fallback Override

Hooks DirectWrite's font fallback system to override font selection for specific
Unicode character ranges across all applications.

## Features
- Global font fallback override
- Per-character-range customization
- Real-time configuration updates

## Usage
Configure fallback rules in settings to map character ranges to specific fonts.
For example, force all CJK characters (U+4E00-U+9FFF) to use "Microsoft YaHei".
