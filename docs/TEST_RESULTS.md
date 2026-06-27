# Test Results Summary

## Environment used for sale-ready validation

The sale-ready package was checked in a clean local build workflow.

## Confirmed checks

- CMake configure: PASS
- CMake build: PASS
- Sale smoke test: PASS
- Release consistency gate: PASS
- Release audit gate: PASS

## Sale smoke flow

The sale smoke test validates the core buyer-relevant workflow:

1. Create a new `.eov` volume
2. Import sample files
3. List volume contents
4. Verify integrity
5. Show storage statistics
6. Read a byte range from compressed volume data
7. Export a file
8. Compare exported output with source data

Result:

```text
SALE_SMOKE_PASS
```

## CTest status

- Total registered tests: 64
- Passed: 58
- Skipped by design: 6
- Failed: 0

## Important limitation

The native Windows driver/mount path is experimental. The strongest validated layer is the read-only compressed volume/archive core and CLI.
