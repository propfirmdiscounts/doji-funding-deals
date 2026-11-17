# Doji Funding Discount Code, Deals History & Dataset

As of November 2026, the verified Doji Funding discount code is PFD — 60% OFF, which can be applied on the checkout page anytime. The newest is "60% off every challenge, plus reset savings with code PFD".

- Code: PFD
- Discount: 60% off (what the code takes off the firm's newest deal; it applies to every Doji Funding deal, whatever form that deal is stated in)
- Valid: Standing code — no published expiry date
- Last deal published: 2026-11-02
- GitHub repository: [Doji Funding Discount Code & Deals History Repository](https://github.com/propfirmdiscounts/doji-funding-deals)
- Firm page: [Doji Funding Page on PropFirmDiscount](https://propfirmdiscount.com/prop-firm/doji-funding/)
- Full dataset: [All Prop Firm Discount Codes Dataset](https://github.com/propfirmdiscounts/prop-firm-discount-codes)
- Code record: [Doji Funding API Record](https://propfirmdiscount.com/api/prop-firm-codes/)

## Latest Doji Funding deal: 60% off every challenge, plus reset savings with code PFD

- Published: 2026-11-02
- Offer ends: 2026-11-08 (ended)
- Offer: 60% off
- Scope: 1-Step And 2-Step Challenges
- Code: PFD
- Deal page: [Doji Funding Deal Page](https://propfirmdiscount.com/deals/doji-funding/doji-funding-election-day-60-percent-off/)

## Doji Funding Discount Code & Deals History FAQ

**What is the Doji Funding discount code?**

PFD. It is verified by PropFirmDiscount.com and takes 60% off Doji Funding challenges and accounts.

**Does the Doji Funding discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current Doji Funding deal?**

**60% off every challenge, plus reset savings with code PFD** — published 2026-11-02. Offer ends: 2026-11-08 (ended). The offer is 60% off.

---

## Doji Funding Deals History

Total deals tracked: **3**

### 2026 (3 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2026-11-02 | Doji Funding: 60% off every challenge, plus reset savings with code PFD | 60% off | 2026-11-08 (ended) | — | [View Deal](https://propfirmdiscount.com/deals/doji-funding/doji-funding-election-day-60-percent-off/) |
| 2026-10-26 | Doji Funding: 60% Off All Challenges for Halloween with code PFD | 60% off | 2026-10-31 (ended) | Halloween | [View Deal](https://propfirmdiscount.com/deals/doji-funding/doji-funding-halloween-60-off-every-challenge/) |
| 2026-10-12 | Doji Funding: 30% Off Every Configurable Evaluation Account with code PFD | 30% off | 2026-10-12 (ended) | — | [View Deal](https://propfirmdiscount.com/deals/doji-funding/doji-funding-launch-day-30-off/) |

---

## About the Doji Funding Discount Code & Deals History Dataset

This repository mirrors every deal **Doji Funding** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: [PropFirmDiscount.com](https://propfirmdiscount.com)
- Prop firm profile: [Doji Funding Profile](https://propfirmdiscount.com/prop-firm/doji-funding/)
- All firms: [All Prop Firms Directory](https://github.com/propfirmdiscounts/prop-firm-discount-codes)

## Doji Funding Deals History Dataset: Field Definitions

One row per deal. The first fields are the observation exactly as the
PropFirmDiscount API returns it; the firm's own code fields and the
links are appended after, in the order below.

| Field | Meaning |
|---|---|
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `offer_type` | The kind of offer as recorded on the site. |
| `discount_value` | How this deal is stated on the site, in whatever form the firm uses: a percentage (`50%`), a price (`$39`), a BOGO (`Buy 1 Get 1`), a freebie (`Free Reset`). Not the code's rate. |
| `scope` | What the deal covers. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `event` | The seasonal campaign this deal was tagged with on the site (`Halloween`, `Black Friday`), or `null` when it belongs to no event. The event never changes what the deal is worth — it names the occasion the deal was run for. |
| `last_verified` | The date this deal's details were last checked. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Data Freshness & Verification

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## Data License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to [PropFirmDiscount.com](https://propfirmdiscount.com).
