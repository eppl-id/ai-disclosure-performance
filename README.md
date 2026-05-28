# AI-related Disclosure & Firm Performance


ExInt II: Research Designs in SME Research | WU Vienna | SS 2026

## Research Question

Does R&D intensity influence firm performance among listed firms?

More specifically, this project investigates whether firms with higher R&D intensity show higher accounting-based performance, measured by Return on Assets (RoA).


## Theoretical Background

| Theory / Literature Stream | Key Claim | Implication for AI Disclosure–Performance |
|---|---|---|
| AI-related disclosure and firm performance | Firms increasingly report on artificial intelligence as part of their strategic and technological positioning. | AI-related disclosure can be used as a text-based indicator of a firm's AI orientation or AI focus. |
| Textual analysis of corporate reports | Annual reports and 10-K filings contain relevant information about firm strategy, innovation and technological focus. | AI-related keywords in corporate reports can be extracted and transformed into measurable variables. |
| Resource-based view / capability perspective | Digital and AI-related capabilities may help firms improve efficiency, innovation and decision-making. | A higher level of AI-related disclosure may be associated with stronger firm performance. |
| Narrative disclosure literature | Corporate disclosure does not only provide financial information, but also communicates strategic priorities and expectations. | AI-related disclosure may reflect either actual AI-related activities or strategic communication. |
| Firm performance research | Firm performance can be measured through accounting-based and market-based indicators. | ROA, Tobin's Q, sales growth or operating margin may be used as dependent variables. |

## Hypotheses

H1: R&D intensity is positively associated with firm performance.


## Variables

### Dependent variable (Y)

| Construct | Data Item(s) | Formula | Source |
|---|---|---|---|
| Return on Assets (RoA) | `NICON`, `AT` | `NICON / AT` | WRDS / Compustat |

### Independent variable (X)

| Construct | Data Item(s) | Formula | Source |
|---|---|---|---|
| R&D Intensity | `XRD`, `AT` | `XRD / AT` | WRDS / Compustat |

### Controls

| Construct | Data Item(s) | Formula | Source |
|---|---|---|---|
| Firm size | `AT` | `log(AT)` | WRDS / Compustat |
| Leverage | `DLTT`, `DLC`, `SEQ` | `(DLTT + DLC) / SEQ` | WRDS / Compustat |
| Firm age | `FYEAR`, `INCO` | `FYEAR - INCO` | WRDS / Compustat |
| Industry | `SIC` | categorical | WRDS / Compustat |
| Year | `FYEAR` | categorical | WRDS / Compustat |

## Key References

| Reference | Research Context | Key Concept | Relevance for This Project |
|---|---|---|---|
| Mishra et al. (2022) | AI focus in corporate filings and firm performance | AI keyword frequency, firm performance | Serves as one of the main anchor studies for measuring AI-related disclosure using text-based indicators. |
| Giordino et al. (2026) | AI-related disclosure in European firms | AI disclosure, ROA, Tobin's Q, ESG | Provides a closely related European reference point and helps define possible dependent variables. |
| Denicolai et al. (2021) | Artificial intelligence, firm capabilities and internationalisation | AI readiness, capabilities, internationalisation | Supports the theoretical argument that AI-related capabilities can influence firm-level outcomes. |
| Alduais (2024) | Narrative disclosure and textual analysis in corporate reporting | Disclosure quality, business reports, text analysis | Helps justify the use of annual reports as a data source for measuring AI-related disclosure. |
| Ahmed et al. (2025) | Textual characteristics in corporate reporting | Tone, readability, disclosure quality | Relevant for possible extensions beyond simple AI keyword counts. |

