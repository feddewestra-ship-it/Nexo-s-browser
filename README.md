# Nexo Browser – Exit Codes Documentation

This document lists all possible return codes for Nexo Browser installer and executable.

## Exit Codes

| Code | Meaning |
|------|--------|
| 0 | Success – application closed normally |
| 1 | General error |
| 2 | Installation error |
| 3 | Missing dependencies |
| 4 | File access denied |
| 5 | Network failure (update/download issue) |
| 6 | Unknown critical failure |

## Notes
- Exit code 0 always indicates successful execution.
- Any non-zero value indicates an error state.
- Codes may be extended in future versions.
