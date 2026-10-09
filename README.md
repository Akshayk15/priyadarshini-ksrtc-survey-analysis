# Priyadarshini Scheme – Impact Analysis (KSRTC Survey)

Survey-based analysis of **1,417 responses** on how Kerala's Priyadarshini free-travel scheme affects passengers, private bus operators and KSRTC operations.

🔗 **Live dashboard:** [ksrtc-insight.lovable.app](https://ksrtc-insight.lovable.app/)

![Overview](images/01_overview.png)

## Objective
Understand perceived passenger benefits, the shift from private buses to KSRTC, the pressure on private operators, and the operational challenges (overcrowding, delays) KSRTC faces, and what respondents want done about it.

## Dataset
- 1,417 responses, 24 columns, unique response IDs, no duplicates
- Demographics: age group, gender, district (11), area (rural / semi-urban / urban), occupation
- Usage and impact: KSRTC usage, expense reduction, economic benefit, private-bus usage, KSRTC shift, reasons for shifting
- Operations: overcrowding, peak periods, delays, expected future impacts, preferred solutions

## Key Insights
| Metric | Result |
|---|---|
| Reported reduced travel expenses | 72.5% (1,190 valid responses) |
| Frequent KSRTC use (daily / several times a week) | 45.3% |
| Significant shift toward KSRTC | 28.5% (1,183 valid responses) |
| Frequent overcrowding (always / often) | 71.6% |
| Moderate or significant private-bus impact | 70.4% |
| Top reason for using KSRTC | Lower / zero travel cost (36.0%) |
| Most preferred solution | Student & worker services (53.2%) |
| Peak period | Morning and evening (51.4%) |

> Patterns reflect respondent perceptions and associations, not proven causation.

## Dashboard Sections
1. Respondent profile
2. Passenger benefits: affordability, economic benefit, mode shift
3. Impact on private bus operators
4. KSRTC operational challenges: overcrowding, peaks, delays
5. Expected future impact and preferred solutions
6. Key relationships across variables

Filters: age group, gender, district, area, occupation, KSRTC usage, private-bus usage.

## Dashboard Screenshots
![Filters](images/02_filters.png)
![Passenger benefits](images/03_passenger_benefits.png)
![Private bus impact](images/04_private_bus_impact.png)
![Operational challenges](images/05_operational_challenges.png)
![Key relationships](images/06_key_relationships.png)

## Project Structure
```
├── README.md
├── data/        # survey CSV
├── python/      # cleaning + EDA notebook
├── sql/         # analysis queries
├── powerbi/     # .pbix file
└── images/      # dashboard screenshots
```

## Author
Akshay K
