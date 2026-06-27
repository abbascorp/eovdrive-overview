# EOVDrive Sale Summary

## One-line description

C++ compressed virtual volume/archive engine with smart codec selection, verification, CLI tools, and experimental Windows mount support.

## Project vision

EOVDrive aims to make storage smarter. The project is built around a `.eov` virtual volume format that stores files as verified compressed chunks. The design goal is to evaluate available compression strategies, keep the best valid representation, and still allow reliable read-back from the compressed volume.

The long-term product direction is a Windows-focused compressed virtual drive: users store files in a compact `.eov` volume and access them through normal tools without manually extracting everything first.

## What is working

- C++ core engine builds
- CLI flow works for core archive/volume operations
- Create volume
- Import files
- Export files
- List volume contents
- Verify integrity
- Show stats
- Read byte ranges from compressed volume data
- Chunk/manifest/index-based volume layout
- Multiple codec implementations
- Test and validation materials included in the private sale package

## What is experimental

- Native Windows driver/mount layer
- ProjFS/native mount path
- Write support
- Installer/product polish

## What is included after sale

- Full source package
- Tests and validation scripts
- Documentation
- Sample volumes
- Windows service/installer/driver prototype code
- Handoff checklist

## Honest status

This is a technical asset, not a finished consumer product. The strongest asset is the working read-only compressed volume/archive engine and CLI. The Windows mount/driver layer is included as experimental prototype work.
