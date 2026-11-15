# Korea Event Base Rates

**Live site: https://aroundble.github.io/korea-event-base-rates/**

What did Korean (KOSPI/KOSDAQ) stocks do after each type of corporate disclosure? This site publishes
historical *base rates* — average, median and share-of-positive excess returns vs the market index — for
~74,000 KRX KIND disclosures (December 2021 – October 2026), broken down by disclosure type, timing
(before open / during session / after close) and liquidity.

한국 상장사 공시 유형별로 공시 이후 주가가 지수 대비 어떻게 움직였는지 보여주는 과거 통계 사이트입니다.

## Contents

- **Event-type pages** — distribution and base rates at +1, +5, +20 trading days for buybacks, convertible bonds,
  rights issues, supply contracts, preliminary earnings, dividends, largest-shareholder changes and more.
- **Daily feed** — disclosures from the last 10 trading days, each shown next to the historical base rate of the
  same type × timing × liquidity group. Refreshed after the Korean market close on trading days.
- **Company pages** — every company with 3+ tracked disclosures: its disclosure history and the excess return after each.

## Method (short)

- Source: KRX KIND disclosure list with minute timestamps; corrected filings and duplicates removed.
- Entry: before 09:00 → same-day open; 09:00–15:20 → same-day close; after 15:20 → next-day open.
- Return: to the close of entry day +1/+5/+20 trading days minus the KOSPI or KOSDAQ index return, net of Korean trading costs.
- Liquidity: 20-day average traded value before the disclosure (under ₩1bn, ₩1–10bn, ≥₩10bn per day).
- Robust ●: sample split in half by date; both halves have the same sign and |t| > 2.
- Only derived statistics are published; no raw price data is redistributed.

Limitations: ~5 years of data, overlapping events, survivorship not fully controlled, classification by filing title.

## Disclaimer

Statistics only — **not investment advice**. This site provides general, non-personalized historical statistics
to everyone equally. It does not recommend buying or selling any security, does not provide advice to any
individual, and nothing here is an offer or solicitation. Past base rates do not guarantee future returns.

본 사이트는 누구에게나 동일하게 제공되는 일반적인 과거 통계 정보이며, 특정 종목의 매매 권유·추천이나 개인별 투자 자문이 아닙니다.
투자 판단과 책임은 이용자 본인에게 있습니다.
