# AI-related Disclosure & Firm Performance

Zuerst Demo Machen mit 5 Unternehmen, danach ändern auf Variablen, danach die taskfile
oder python 01_pull_data.py in python ausführen, für pull und clean machen - gucken update von den py dateien, da wird aber bei clean irgendwas gefiltert - ist gefiltert auf EUR Jahresabschluss, sonst nochmal nachschauen, sonst session 4 auch nochmal Variablen anschauen, mit welcher variable komme ich dann da zur Hypothese?!
ExInt II: Research Designs in SME Research | WU Vienna | SS 2026

## Research Question

Does AI-related disclosure in corporate annual reports have a relationship with firm performance?


## Theoretical Background

| Theory / Literature Stream | Key Claim | Implication for AI Disclosure–Performance |
|---|---|---|
| AI-related disclosure and firm performance | Firms increasingly report on artificial intelligence as part of their strategic and technological positioning. | AI-related disclosure can be used as a text-based indicator of a firm's AI orientation or AI focus. |
| Textual analysis of corporate reports | Annual reports and 10-K filings contain relevant information about firm strategy, innovation and technological focus. | AI-related keywords in corporate reports can be extracted and transformed into measurable variables. |
| Resource-based view / capability perspective | Digital and AI-related capabilities may help firms improve efficiency, innovation and decision-making. | A higher level of AI-related disclosure may be associated with stronger firm performance. |
| Narrative disclosure literature | Corporate disclosure does not only provide financial information, but also communicates strategic priorities and expectations. | AI-related disclosure may reflect either actual AI-related activities or strategic communication. |
| Firm performance research | Firm performance can be measured through accounting-based and market-based indicators. | ROA, Tobin's Q, sales growth or operating margin may be used as dependent variables. |

## Hypotheses

H1: AI-related disclosure is positively associated with firm performance.


## Key variables:

| Variable | Compustat field(s) / Calculation | Description |
|---|---|---|
| ROA | `ib / at` or `ni / at` | Return on assets; main accounting-based performance measure |
| AI disclosure | `AI keyword count / total words` | AI-related disclosure intensity from annual reports or 10-K filings |
| Operating margin | `oiadp / sale` | Operating profitability |
| Sales growth | `(sale_t - sale_t-1) / sale_t-1` | Revenue growth compared to the previous year |
| Market-to-book | `mkvalt / ceq` | Market-based performance or valuation measure |
| R&D intensity | `xrd / at` or `xrd / sale` | R&D expenditure scaled by total assets or sales |
| Firm size | `log(at)` | Log total assets |
| Leverage | `(dltt + dlc) / at` | Total debt divided by total assets |
| Industry | `sic` or `naics` | Industry controls |
| Year | `fyear` | Year controls |

Note: The AI disclosure variable is not directly available in Compustat. It will be constructed from annual reports or 10-K filings using a keyword-based text analysis approach.

## Key References

| Reference | Research Context | Key Concept | Relevance for This Project |
|---|---|---|---|
| Mishra et al. (2022) | AI focus in corporate filings and firm performance | AI keyword frequency, firm performance | Serves as one of the main anchor studies for measuring AI-related disclosure using text-based indicators. |
| Giordino et al. (2026) | AI-related disclosure in European firms | AI disclosure, ROA, Tobin's Q, ESG | Provides a closely related European reference point and helps define possible dependent variables. |
| Denicolai et al. (2021) | Artificial intelligence, firm capabilities and internationalisation | AI readiness, capabilities, internationalisation | Supports the theoretical argument that AI-related capabilities can influence firm-level outcomes. |
| Alduais (2024) | Narrative disclosure and textual analysis in corporate reporting | Disclosure quality, business reports, text analysis | Helps justify the use of annual reports as a data source for measuring AI-related disclosure. |
| Ahmed et al. (2025) | Textual characteristics in corporate reporting | Tone, readability, disclosure quality | Relevant for possible extensions beyond simple AI keyword counts. |

