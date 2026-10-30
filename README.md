# Timezone Data

> All IANA timezones with UTC offsets, DST rules, and country mapping

**Category:** dev-ref · **Data:** IANA tz database · **License:** public-domain · **Updates:** yearly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/timezones.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/timezone-data/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/timezone-data/data.json');
const data = await res.json();
```

## Data

- Source: IANA tz database
- License: public-domain
- Last updated: `2026-08-25T03:10:21.696Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/timezone-data/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

public-domain
