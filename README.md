# AdGuard Social Media Filter

A small AdBlock-syntax filter list that blocks X (Twitter) and Instagram
at the DNS level.

## Usage

Add the raw list URL as a custom filter/blocklist source:

```
https://raw.githubusercontent.com/Rodrigora/ad-guard-social-medical-filter/main/list.txt
```

- **AdGuard DNS**: Settings → your DNS server → User rules → paste the
  contents of `list.txt`, or add the raw URL under Blocklists → Add a
  custom list.
- **AdGuard Home**: Filters → DNS blocklists → Add blocklist → paste the
  raw URL above.
