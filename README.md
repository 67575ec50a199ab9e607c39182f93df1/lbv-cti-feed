# CTI Feed

Threat intelligence feed — machine-readable IOC lists.

## Endpoints

| Type   | Raw URL |
|--------|---------|
| IP     | `.../feed/ip.txt`     |
| Domain | `.../feed/domain.txt` |
| Hash   | `.../feed/hash.txt`   |

## Format

- One entry per line  
- `#` lines are comments  
- UTF-8 / LF

## Notes

Add = block. Remove = unblock. No other metadata.
