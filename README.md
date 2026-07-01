# Email Deliverability Data

Open, **daily-updated** dataset on how the world configures email — **MX provider market share, SPF & DMARC adoption** — measured by [MailTester Ninja](https://mailtester.ninja) via aggregate DNS scans of a representative panel of domains.

**Privacy:** domain-level configuration only. **No personal data, no email addresses, no email content.**

- 📊 Live dashboard: **https://deliverability.mailtester.ninja**
- 🔌 JSON API: https://deliverability.mailtester.ninja/api/index.json

## Files
| file | content |
|---|---|
| `index.json` | latest full snapshot (headline + provider/SPF/DMARC breakdowns) |
| `mx_provider_share.csv` | MX provider market share |
| `history/headline.csv` | daily time-series of headline metrics |

## License
**CC BY 4.0** — free to reuse, share and build upon **with attribution to MailTester Ninja**.

_Updated automatically every day by MailTester Ninja._
