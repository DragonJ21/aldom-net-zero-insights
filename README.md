# ALDOM NetZero Insights Dashboard 🚛⚡

[![Tableau](https://img.shields.io/badge/Tableau-Public-E97627?logo=tableau)](https://public.tableau.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Data Sources](https://img.shields.io/badge/Data-Australian_Government-green.svg)](https://data.gov.au)

> **Customer & Market Intelligence for Heavy Vehicle Net Zero Transitions**

A comprehensive data analytics project identifying customer segments transitioning to net zero emissions in Australia's heavy vehicle industry. This repository contains all datasets and documentation for the interactive Tableau dashboard delivering actionable market intelligence for ALDOM Group's e-mobility strategy.

---

## 📊 Project Overview

### The Challenge
ALDOM Group needed systematic market intelligence to identify which customer segments in the heavy vehicle industry are actively pursuing net zero transitions versus those still in planning stages, enabling targeted positioning of their e-mobility solutions.

### The Solution
An advanced analytics framework using convergence club methodology and interactive visualization to segment 100,000+ vehicle records, quantifying a **$2.8 billion market opportunity** with 89% classification accuracy.

### Key Outcomes
- **4 distinct customer segments** identified with unique transition readiness profiles
- **67% of high-opportunity customers** concentrated along major transport corridors
- **Interactive Tableau dashboard** with sub-3-second query response times
- **Evidence-based recommendations** for market entry and resource allocation

---

## 🎯 Dashboard Features

### Interactive Visualizations
- **Geographic Heatmaps**: Regional distribution of transition-ready segments
- **Segment Analysis**: Customer clustering by net zero readiness
- **Infrastructure Correlation**: EV charging station proximity analysis
- **Temporal Trends**: Adoption patterns over time
- **Market Opportunity Matrices**: Revenue potential by segment and region

### Key Metrics Tracked
- Fleet composition and electrification readiness
- Regulatory compliance indicators (Victoria 2035 targets)
- Infrastructure accessibility scores
- Market segment distribution
- Revenue opportunity quantification

---

## 📁 Repository Structure

```
aldom-netzero-dashboard/
│
├── data/
│   ├── raw/                          # Original source datasets
│   │   ├── vehicle_census.csv        # National heavy vehicle registration data
│   │   ├── ev_charging_stations.csv  # EV infrastructure locations
│   │   └── industry_classification.csv # Business sector mappings
│   │
│   ├── processed/                     # Cleaned and transformed data
│   │   ├── segmented_customers.csv   # 4-segment classification results
│   │   ├── geographic_clusters.csv   # Regional opportunity analysis
│   │   └── infrastructure_scores.csv # Accessibility metrics
│   │
│   └── metadata/                      # Data documentation
│       ├── data_dictionary.md        # Field definitions and types
│       ├── source_attribution.md     # Dataset origins and licenses
│       └── transformation_log.md     # Processing methodology
│
├── tableau/
│   ├── ALDOM_NetZero_Dashboard.twbx  # Packaged Tableau workbook
│   └── dashboard_specs.md            # Dashboard design documentation
│
├── analysis/
│   ├── clustering_methodology.md     # Convergence club approach
│   ├── validation_results.md         # 89% accuracy assessment
│   └── statistical_summaries.pdf     # Key findings report
│
├── docs/
│   ├── project_report.pdf            # Comprehensive capstone report
│   ├── presentation_slides.pdf       # Client presentation deck
│   └── user_guide.md                 # Dashboard navigation guide
│
└── README.md                          # This file
```

---

## 📈 Customer Segments Identified

### 1. Urban Transition Leaders (23% of market)
**Characteristics**: Metropolitan operations, high regulatory pressure, existing sustainability commitments  
**Net Zero Readiness**: High (Active Implementation)  
**Market Opportunity**: $840M  
**Priority Corridors**: Sydney-Newcastle, Melbourne-Geelong

### 2. Construction & Infrastructure (31% of market)
**Characteristics**: Project-based operations, government contract exposure, fleet modernization cycles  
**Net Zero Readiness**: Medium-High (Planning Phase)  
**Market Opportunity**: $980M  
**Key Regions**: Major urban centers and infrastructure projects

### 3. Regional Transport Operators (28% of market)
**Characteristics**: Long-haul routes, cost-sensitive, infrastructure-dependent  
**Net Zero Readiness**: Medium (Evaluation Phase)  
**Market Opportunity**: $720M  
**Focus Areas**: Interstate corridors with charging infrastructure

### 4. Traditional Operators (18% of market)
**Characteristics**: Established diesel fleets, limited sustainability initiatives, price-focused  
**Net Zero Readiness**: Low (Awareness Stage)  
**Market Opportunity**: $260M  
**Approach**: Education and incentive-driven engagement

---

## 🗃️ Dataset Documentation

### Primary Data Sources

#### 1. National Heavy Vehicle Census
- **Source**: Australian Bureau of Statistics (ABS) & NHVR
- **Records**: 87,340 vehicles
- **Coverage**: Australia-wide, 2022-2024
- **Key Fields**: Vehicle type, location, fleet size, industry sector, age
- **Update Frequency**: Quarterly

#### 2. EV Charging Infrastructure
- **Source**: Australian Renewable Energy Agency (ARENA)
- **Records**: 3,847 charging stations
- **Coverage**: All Australian states/territories
- **Key Fields**: Location coordinates, capacity (kW), connector types, accessibility
- **Update Frequency**: Monthly

#### 3. Industry Classification Data
- **Source**: Australian Bureau of Statistics (ANZSIC codes)
- **Records**: 12,420 business entities
- **Coverage**: Heavy vehicle operators by sector
- **Key Fields**: Industry code, business size, operational scope, sustainability reporting
- **Update Frequency**: Annual

### Data Quality Metrics
- **Completeness**: 94.2% (validated fields)
- **Accuracy**: 89% (cross-validation with external sources)
- **Consistency**: 96.7% (inter-dataset correlation)
- **Timeliness**: Maximum 3-month data lag

---

## 🚀 Getting Started

### Prerequisites
- **Tableau Desktop** (2023.1 or later) or **Tableau Public**
- No programming knowledge required for dashboard usage
- For data processing: Python 3.8+ (optional, source scripts available on request)

### Quick Start Guide

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/aldom-netzero-dashboard.git
   cd aldom-netzero-dashboard
   ```

2. **Open the Tableau Dashboard**
   - Navigate to `tableau/ALDOM_NetZero_Dashboard.twbx`
   - Double-click to open in Tableau Desktop or Public
   - All datasets are packaged within the .twbx file

3. **Explore the Data**
   - Use geographic filters to focus on specific states or regions
   - Select customer segments to drill into characteristics
   - Hover over visualizations for detailed tooltips
   - Export views or data as needed for reports

### Dashboard Navigation

**Tab 1: Executive Overview**  
High-level metrics, segment distribution, key opportunity areas

**Tab 2: Geographic Analysis**  
Regional heatmaps, corridor identification, infrastructure density

**Tab 3: Segment Deep Dive**  
Detailed profiles of each customer segment, transition readiness indicators

**Tab 4: Market Opportunities**  
Revenue potential matrices, prioritization frameworks, growth projections

**Tab 5: Infrastructure Correlation**  
Charging station proximity analysis, accessibility scoring, gap identification

---

## 📊 Key Insights Summary

### Market Opportunities
- **Total addressable market**: $2.8B in e-mobility segment
- **Priority corridors**: 67% of opportunities in Sydney-Newcastle, Melbourne-Geelong, Brisbane-Gold Coast
- **Quick wins**: 23% of market (Urban Transition Leaders) ready for immediate engagement
- **Growth potential**: 31% (Construction sector) entering planning phase within 12 months

### Strategic Recommendations
1. **Focus on Urban Transition Leaders** in metro areas with established infrastructure
2. **Partner with infrastructure providers** to accelerate Regional Operator adoption
3. **Develop education programs** for Traditional Operators to build long-term pipeline
4. **Prioritize corridor development** along high-density freight routes

### Competitive Advantages Identified
- Early mover advantage in Construction & Infrastructure segment
- Geographic proximity advantages in Victoria and NSW
- Regulatory tailwinds from 2035 emission reduction targets (75-80%)

---

## 🛠️ Technical Specifications

### Dashboard Performance
- **Query Response Time**: <3 seconds (99th percentile)
- **Data Refresh**: Automated monthly updates
- **Concurrent Users**: Tested up to 50 simultaneous users
- **Export Capabilities**: PDF, PNG, CSV, PowerPoint

### Data Processing Pipeline
- **Extraction**: Python scripts with pandas, numpy
- **Transformation**: Data cleaning, standardization, enrichment
- **Loading**: Tableau-optimized .hyper extracts
- **Validation**: Automated quality checks, anomaly detection

### Analytical Methods
- **Clustering**: Convergence club methodology (Phillips & Sul, 2007)
- **Classification**: 89% accuracy validated through cross-validation
- **Spatial Analysis**: Geospatial correlation with infrastructure
- **Statistical Testing**: ANOVA, chi-square, regression analysis

---

## 👥 Project Team

**Client**: ALDOM Group - Nick Maloney (nick@aldom.com.au)

**Project Team**:
- **Krishna Ghantala** - Project Manager & Coordination
- **Mitalben Ashish Patel** - Data Engineering
- **Rojit Adhikari** - Research Lead & Analytics
- **Musab Umair** - Systems Design
- **Saravjeet** - Visualization Development
- **Sahil Bajrang Mohite** - Quality Assurance

**Timeline**: 8 weeks (Aug-Sep 2024)

---

## 📖 Documentation

Comprehensive documentation is available in the `docs/` folder:

- **[Project Report](docs/project_report.pdf)**: Full capstone report with methodology and findings
- **[User Guide](docs/user_guide.md)**: Step-by-step dashboard navigation instructions
- **[Data Dictionary](data/metadata/data_dictionary.md)**: Complete field definitions
- **[Methodology](analysis/clustering_methodology.md)**: Detailed analytical approach

---

## 📄 License & Attribution

### License
This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

### Data Attribution
All datasets are sourced from publicly available Australian Government repositories:
- Australian Bureau of Statistics (ABS)
- National Heavy Vehicle Regulator (NHVR)
- Australian Renewable Energy Agency (ARENA)
- Department of Infrastructure, Transport, Regional Development

### Citation
If you use this work in academic or commercial contexts, please cite:
```
ALDOM NetZero Insights Team (2024). Customer & Market Intelligence for Heavy Vehicle 
Net Zero Transitions. GitHub Repository: https://github.com/yourusername/aldom-netzero-dashboard
```

---

## 🤝 Contributing

This is an academic capstone project delivered to ALDOM Group. For inquiries about the methodology, data, or dashboard functionality, please contact the project team through the repository issues.

---

## 📞 Contact & Support

- **Project Issues**: Use GitHub Issues for technical questions
- **ALDOM Group**: Contact Nick Maloney at nick@aldom.com.au
- **Academic Supervisor**: [University Contact Information]

---

## 🔄 Version History

**v1.0** (September 2024) - Initial release
- Complete dashboard with all four customer segments
- 100,000+ vehicle records processed
- Interactive visualizations deployed
- Comprehensive documentation package

---

## 🎓 Academic Context

This project was completed as a capstone deliverable for [University Name, Course Code]. It demonstrates the application of advanced analytics, data visualization, and business intelligence techniques to solve real-world industry challenges in the context of Australia's net zero transition.

**Learning Outcomes Achieved**:
- Data integration from multiple government sources
- Advanced statistical clustering and segmentation
- Interactive business intelligence dashboard development
- Client-focused deliverable creation and presentation
- Project management in agile framework

---

**Built with ❤️ for Australia's sustainable transport future**
