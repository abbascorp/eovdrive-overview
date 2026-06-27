# SideProjectors Listing Text

## Title

C++ Compressed Virtual Volume / Archive Engine — Full Source Code

## Price

$750 OBO

## Short description

C++ compressed virtual volume/archive engine with smart codec selection, verification, CLI tools, and experimental Windows mount support.

## Full description

EOVDrive is a pre-revenue C++ technical asset built around a compressed and verifiable virtual volume format called `.eov`.

The vision of the project is to make storage smarter: instead of blindly storing files in one fixed way, EOVDrive breaks data into chunks, evaluates compression strategies, stores the best valid representation, verifies integrity, and allows files to be read back reliably from the compressed volume.

The strongest working part is the core engine and CLI. It can create `.eov` volumes, import files, export files, list volume contents, verify integrity, show storage statistics, and read byte ranges from compressed data without requiring the full file to be extracted first.

Included in the sale:

- Full C++ source code
- CMake build system
- CLI tool
- Multiple codec implementations
- Chunk/manifest/index-based volume format
- Validation scripts and tests
- Documentation
- Sample `.eov` volumes
- Windows service, installer, ProjFS/native driver prototype code

Current status:

- Core engine builds
- CLI smoke flow works
- Release consistency gates are cleaned up
- Read-only compressed volume/archive use case is the strongest part
- Smart codec/strategy selection is part of the project direction
- Compressed files can be opened/exported/read back through the core tools
- Native Windows driver/mount layer is experimental and not production-ready
- Write support is not production-ready

This is not being sold as a finished consumer product. It is a serious technical asset for a developer or small team interested in compression, archive formats, Windows storage tooling, virtual filesystems, or developer utilities.

Best buyer:
A C++/Windows/storage/compression developer who wants to continue, repurpose, or productize the project.

Reason for selling:
I want the project to go to someone technical who can continue development and turn it into a polished product.

Fast-close offers around $500-$600 may be considered.
