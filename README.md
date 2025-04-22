<div align="center">

# DNS Filters

![Cybersight Security DNS Filters](assets/logo.png)

The Cybersight Security DNS Filters repository houses a curated collection of DNS filter lists, accumulated over several years. These lists are designed to enhance network security and efficiency by blocking unwanted or harmful domains.

</div>

## Features:
- Curated collection of DNS filter lists from multiple sources
- Lists categorized by threat type and use case
- Regularly updated with new domains
- Easy to integrate with most DNS filtering solutions
- Lightweight and optimized for performance

## Contents
The repository contains multiple DNS filter lists, each tailored for different use cases or threats. These lists may include, but are not limited to, filters for:

- Advertisements
- Tracking domains
- Malware and phishing sites
- Content filters for family-safe browsing

**Important Note:** The filter lists included in this repository are not originally created by Cybersight Security. They have been collected from various public sources over the years and are compiled here for convenience.

## Data Sources
The DNS filters are aggregated from multiple reputable sources including:

- Publicly available blocklists
- Community-maintained filter lists
- Security research publications
- Crowdsourced threat intelligence

## Technical Implementation

### List Maintenance
- Automated scripts to check for updates from source lists
- Deduplication process to optimize list size
- Validation checks for proper DNS format
- Categorization by threat type

### Integration Options
- Compatible with Pi-hole, AdGuard Home, and similar DNS filters
- Can be used with enterprise DNS security solutions
- Suitable for personal use on routers or devices

## Installation and Usage

### Requirements
- DNS filtering solution (Pi-hole, AdGuard, etc.)
- Basic knowledge of DNS configuration

### Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/cybersight/dns-filters.git
   cd dns-filters
   ```

2. **Choose the appropriate filter list(s) for your needs**

3. **Import into your DNS filtering solution:**
   - Follow your DNS solution's documentation for adding external blocklists
   - Typically involves adding the raw URL of the list file

4. **Update your DNS resolver to apply changes**

## Configuration
You can customize the usage by:

- Selecting specific lists based on your needs
- Combining with other blocklists
- Adjusting update frequency based on your requirements

## License
This project is licensed under the GNU General Public License (GPL). This means you are free to:

- Use the software for any purpose
- Study how the software works and modify it
- Distribute copies
- Distribute modified versions

The full license text is included in the repository.

## About Cybersight Security
Cybersight Security is a leading provider of cybersecurity solutions, helping organizations protect their digital assets against evolving threats. Our DNS Filters repository is part of our commitment to security awareness and education.

**Disclaimer:** This tool is for informational purposes only. Cybersight Security makes no warranties about the completeness or accuracy of the data presented. Users should evaluate the suitability of these filters for their specific needs.