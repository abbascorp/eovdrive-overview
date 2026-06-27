# Buyer Due Diligence

## What the buyer should verify

Before purchase or during inspection, the buyer should review:

- README and project scope
- CMake build files
- CLI tool behavior
- Codec implementation structure
- `.eov` volume layout
- Sale smoke test script
- Test result summary
- Known limitations
- Third-party dependency/license situation

## Suggested inspection steps

```bash
cmake -S . -B build
cmake --build build
ctest --test-dir build
python3 scripts/sale_smoke_test.py --eovctl build/eovctl
```

Exact binary path may vary by platform and build generator.

## Main strengths

- Working C++ core engine
- Practical CLI workflow
- Verified import/export/list/stats/verify/read-range flow
- Chunked compressed volume format
- Multiple codec paths
- Good foundation for archive, storage, compression, or Windows utility productization

## Known limitations

- No production-ready native Windows driver claim
- Mount/driver layer is experimental
- Write support is not production-ready
- No current users or revenue
- This is a technical source-code asset, not a finished commercial application

## Recommended buyer profile

A buyer should be comfortable with C++, CMake, Windows development concepts, compression/storage tooling, and productizing lower-level technical software.
