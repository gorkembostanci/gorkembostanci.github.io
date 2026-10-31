----------------------- Overview --------------------------
Outsourcing_Panel.csv contains annual employment- and value-added-based outsourcing shares, with one row for each country-year pair. The data are stored in a single, unbalanced panel covering 1991-2025.

All shares are fractions of the corresponding business-economy total (ISIC 05-82 excluding K). For example, 0.10 represents 10 percent. Blank cells indicate that a measure is unavailable for that country-year.

----------------------- Variables --------------------------
country: Country identifier. Codes follow ISO 3166-1 alpha-3, except that the United Kingdom is recorded as UK and the United Arab Emirates as UAE.
year: Calendar year.

Share columns follow the structure:

    [basis]_[definition]_[component]

basis
- emp: Employment-based outsourcing share.
- va: Value-added-based outsourcing share.

definition
- broad: Includes all industries in ISIC Sections M (Professional, scientific and technical activities) and N (Administrative and support service activities).
- benchmark: Excludes industries 74, 75, 77, 79, and 701 from Sections M and N. The included provider industries are 69, 7020, 71-73, 78, and 80-82.
- narrow: Uses the benchmark exclusions but removes all of division 70 rather than only industry 701. The included provider industries are 69, 71-73, 78, and 80-82.

component
- hs: High-skill outsourcing share.
- ls: Low-skill outsourcing share.
- tot: Total outsourcing share.

The file therefore contains 18 share columns: three components for each combination of the two bases and three definitions. See the accompanying manuscript for the precise industry composition of the broad, benchmark, and narrow definitions, the high- and low-skill classification, data sources, and harmonization methodology.

----------------------- Industry Descriptions --------------------------
The definitions use the following ISIC Rev. 4 industries:

- 69: Legal and accounting activities.
- 70: Activities of head offices; management consultancy activities.
- 701: Activities of head offices.
- 7020: Management consultancy activities.
- 71: Architectural and engineering activities; technical testing and analysis.
- 72: Scientific research and development.
- 73: Advertising and market research.
- 74: Other professional, scientific and technical activities.
- 75: Veterinary activities.
- 77: Rental and leasing activities.
- 78: Employment activities.
- 79: Travel agency, tour operator, reservation service, and related activities.
- 80: Security and investigation activities.
- 81: Services to buildings and landscape activities.
- 82: Office administrative, office support, and other business support activities.
