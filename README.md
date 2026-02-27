# awesome-alma

A curated list of awesome Ex Libris Alma & Primo VE repos, tools, and resources.

Inspired by [awesome lists](https://github.com/sindresorhus/awesome). Contributions welcome!

---

## Contents

- [Official Ex Libris](#official-ex-libris)
- [API Client Libraries](#api-client-libraries)
- [Primo Development & Customization](#primo-development--customization)
- [Primo VE Normalization & Discovery](#primo-ve-normalization--discovery)
- [Alma Letters (XSL)](#alma-letters-xsl)
- [Cloud Apps](#cloud-apps)
- [Alma Tools & Scripts](#alma-tools--scripts)
- [Analytics & Reporting](#analytics--reporting)
- [Integrations](#integrations)
- [Consortia & Organizations](#consortia--organizations)
- [Individuals](#individuals)
- [Community](#community)

---

## Official Ex Libris

*Repositories maintained by Ex Libris.*

* [ExLibrisGroup](https://github.com/ExLibrisGroup) — Official Ex Libris GitHub organization (119+ repos)
* [primo-explore-devenv](https://github.com/ExLibrisGroup/primo-explore-devenv) — Node.js/Gulp development environment for Primo UI customizations ⭐118
* [primo-explore-package](https://github.com/ExLibrisGroup/primo-explore-package) — Template package for Primo new UI customizations ⭐52
* [SpineOMatic](https://github.com/ExLibrisGroup/SpineOMatic) — Spine label printing for Alma ⭐41
* [customModule](https://github.com/ExLibrisGroup/customModule) — NDE (New Discovery Experience) customization package ⭐31
* [Primo.PNX-context](https://github.com/ExLibrisGroup/Primo.PNX-context) — JSON-LD context for Primo PNX documents ⭐12
* [alma-print-daemon](https://github.com/ExLibrisGroup/alma-print-daemon) — Listens for and prints letters from Alma print queues ⭐11
* [alma-refine](https://github.com/ExLibrisGroup/alma-refine) — App to refine BIB records using OpenRefine services ⭐9
* [Primo-Studio](https://github.com/ExLibrisGroup/Primo-Studio) — Primo Studio ⭐9
* [spineomatic-cloudapp](https://github.com/ExLibrisGroup/spineomatic-cloudapp) — Cloud App version of SpineOMatic ⭐8
* [exl-ezproxy-authenticator](https://github.com/ExLibrisGroup/exl-ezproxy-authenticator) — EZproxy authenticator for Alma ⭐5
* [customModuleExamples](https://github.com/ExLibrisGroup/customModuleExamples) — Examples of NDE custom modules ⭐5
* [ExlTableauWDC](https://github.com/ExLibrisGroup/ExlTableauWDC) — Tableau Web Data Connector for Ex Libris Analytics ⭐4
* [Alma.Converters](https://github.com/ExLibrisGroup/Alma.Converters) — Converters for Alma integrations ⭐4
* [cloudapp-tutorials](https://github.com/ExLibrisGroup/cloudapp-tutorials) — Tutorials for Ex Libris Cloud Apps ⭐1
* [exl-touchnet-connector](https://github.com/ExLibrisGroup/exl-touchnet-connector) — Connector between Alma/Primo and the TouchNet payment system ⭐1
* [MARC-2-BF2](https://github.com/ExLibrisGroup/MARC-2-BF2) — Crosswalk from MARC21 to BIBFRAME2 ⭐1

## API Client Libraries

*Client libraries and wrappers for the Alma REST APIs in various languages.*

### Python
* [almapipy](https://github.com/UCDavisLibrary/almapipy) — Python wrapper for the Alma API (UC Davis) ⭐
* [alma-batch](https://github.com/gwu-libraries/alma-batch) — Asynchronous Python for Alma APIs, supports pandas DataFrames (GWU Libraries)
* [Alma-Helper](https://github.com/MrJeremyHobbs/Alma-Helper) — Rudimentary Python library for Alma APIs
* [nlnzcollservices/Alma-tools](https://github.com/nlnzcollservices/Alma-tools) — Python tools for Alma REST API (National Library of NZ)
* [exl_alma_tools](https://github.com/KoroteevaS/exl_alma_tools) — Middleware between Alma API and Python pipelines

### Ruby
* [alma_rb](https://github.com/tulibraries/alma_rb) — Ruby client for Alma Web Services (Temple University) ⭐
* [alma_api](https://github.com/ubpb/alma_api) — Ruby client library for Alma REST APIs
* [BerkeleyLibrary/alma](https://github.com/BerkeleyLibrary/alma) — Alma/Primo utilities for UC Berkeley Library
* [almarestapi-ruby-lib](https://github.com/jweisman/almarestapi-ruby-lib) — Ruby library for Alma REST APIs

### JavaScript / Node.js
* [alma-utils](https://github.com/UCDavisLibrary/alma-utils) — JavaScript library for Alma API (UC Davis)
* [almarestapi-node-lib](https://github.com/jweisman/almarestapi-node-lib) — Node.js library for Alma REST APIs
* [simple-node-alma-apis](https://github.com/jweisman/simple-node-alma-apis) — Simple Node.js examples for Alma APIs

### PHP
* [dswalker/alma-api](https://github.com/dswalker/alma-api) — PHP client library for Alma and Primo web services

## Primo Development & Customization

*Tools and customization packages for Primo Classic and Primo VE.*

### Development Tools
* [primo-explore-devenv](https://github.com/ExLibrisGroup/primo-explore-devenv) — Official Primo UI dev environment ⭐118
* [dpuwebservices/localDev-primoVE](https://github.com/dpuwebservices/localDev-primoVE) — Local development environment for Primo VE views
* [primo-explore-lod-author-card](https://github.com/jweisman/primo-explore-lod-author-card) — Linked Open Data Author Card for Primo Explore ⭐7
* [primo-explore-libraryh3lp-widget](https://github.com/NYULibraries/primo-explore-libraryh3lp-widget) — LibraryH3lp chat widget for Primo ⭐5
* [primo-explore-course-reserves](https://github.com/alliance-pcsg/primo-explore-course-reserves) — Course reserves module for Primo using Alma API ⭐4
* [Primo-Book-Cover-Carousel](https://github.com/wadeguidry/Primo-Book-Cover-Carousel) — Rotating carousel of book covers from Alma Analytics

### Institutional Customization Packages
* [vculibraries/alma-primo-customizations](https://github.com/vculibraries/alma-primo-customizations) — CSS/JS customizations for Alma and Primo (VCU) ⭐13
* [Los-Rios-Libraries/Primo-VE-Views](https://github.com/Los-Rios-Libraries/Primo-VE-Views) — Primo VE customization package (Los Rios CCD)
* [Brandeis-Library/primo-ve-customization-package](https://github.com/Brandeis-Library/primo-ve-customization-package) — Primo VE customization (Brandeis)
* [rgilmour70/ic-primo-ve](https://github.com/rgilmour70/ic-primo-ve) — Primo VE customization files (Ithaca College)
* [HSG-Library/hsg-primo-view](https://github.com/HSG-Library/hsg-primo-view) — HSG Swisscovery customization package
* [cu-library/primo-customization-package](https://github.com/cu-library/primo-customization-package) — Primo/Omni customization (Carleton University)
* [LincolnUniLTL/primo](https://github.com/LincolnUniLTL/primo) — JavaScript and CSS customizations for hosted Primo (Lincoln University)

## Primo VE Normalization & Discovery

*Normalization rules and discovery enhancements.*

* [primousers/primo-ve-norm](https://github.com/primousers/primo-ve-norm) — Community Primo VE XML normalization rules ⭐29
* [colinbitter/Primo-VE-MARC21-Normalization-Rules](https://github.com/colinbitter/Primo-VE-MARC21-Normalization-Rules) — Customized MARC21 normalization rules for Primo VE ⭐7
* [Alma-Primo-Locate-Tool-Open-Source](https://github.com/LeidenUniversityLibrary/Alma-Primo-Locate-Tool-Open-Source) — Displays locate button in Primo to help patrons find items (Leiden University) ⭐4
* [automate_primo_new_books](https://github.com/LibraryNinja/automate_primo_new_books) — Automates New Book collection maintenance in Alma for Primo VE display ⭐13

## Alma Letters (XSL)

*XSLT customizations for Alma notification letters.*

* [scriptotek/alma-slipsomat](https://github.com/scriptotek/alma-slipsomat) — Tool for syncing Alma letters XSL files with a local folder ⭐15 (archived)
* [uio-library/alma-letters-ubo](https://github.com/uio-library/alma-letters-ubo) — University of Oslo Library XSLT files for Alma letters ⭐8 (archived)
* [blakeegee/alma-letters](https://github.com/blakeegee/alma-letters) — Alma letter templates ⭐7
* [Los-Rios-Libraries/Alma-Letters](https://github.com/Los-Rios-Libraries/Alma-Letters) — Alma letter templates (Los Rios CCD) ⭐5
* [cu-library/alma-letters](https://github.com/cu-library/alma-letters) — Alma letters (Carleton University) ⭐4
* [bisentralen/alma-letters-xslt](https://github.com/bisentralen/alma-letters-xslt) — XSLT style code for Alma letters ⭐3
* [cuny-libraries/alma-letters](https://github.com/cuny-libraries/alma-letters) — Alma letter templates (CUNY) ⭐2
* [Orbis-Cascade-Alliance/slip-templates](https://github.com/Orbis-Cascade-Alliance/slip-templates) — Alma letter templates for local and Summit pick slips

## Cloud Apps

*Alma Cloud Apps for extending functionality.*

* [spineomatic-cloudapp](https://github.com/ExLibrisGroup/spineomatic-cloudapp) — Cloud App version of SpineOMatic ⭐8
* [HSG-Library/alma-copy-user-roles](https://github.com/HSG-Library/alma-copy-user-roles) — Cloud App to copy roles between users ⭐4
* [duke-libraries/dsc-alma-cloudapp](https://github.com/duke-libraries/dsc-alma-cloudapp) — Cloud App for the Data Service Center (Duke)
* [ExLibrisGroup/cloudapp-tutorials](https://github.com/ExLibrisGroup/cloudapp-tutorials) — Official Cloud App tutorials

## Alma Tools & Scripts

*Standalone tools, scripts, and applications for Alma workflows.*

### Cataloging & Metadata
* [alma-refine](https://github.com/ExLibrisGroup/alma-refine) — Refine BIB records using OpenRefine ⭐9
* [OAI-PMH-DC-TO-MARC](https://github.com/MrJeremyHobbs/OAI-PMH-DC-TO-MARC) — Converts Dublin Core metadata to MARC21 for Alma import ⭐7
* [Alma-SRU](https://github.com/MrJeremyHobbs/Alma-SRU) — Module for requesting and parsing SRU data from Alma ⭐6
* [SRU-Searcher](https://github.com/MrJeremyHobbs/SRU-Searcher) — Example script to search Alma using SRU ⭐3
* [MARC-2-BF2](https://github.com/ExLibrisGroup/MARC-2-BF2) — Crosswalk from MARC21 to BIBFRAME2 ⭐1

### Circulation & Fulfillment
* [LazyLists](https://github.com/MrJeremyHobbs/LazyLists) — Scan barcodes to add items to physical item sets in Alma ⭐15
* [RoboReturns](https://github.com/MrJeremyHobbs/RoboReturns) — Bulk returns and in-house checkins in Alma ⭐9
* [Book-Be-Gone](https://github.com/MrJeremyHobbs/Book-Be-Gone) — Withdrawing books through Alma ⭐9
* [AlmaInventory](https://github.com/WRLC/AlmaInventory) — Inventory tool using Alma Bib API (WRLC)

### User Management
* [alma-csv-user-load](https://github.com/ExLibrisGroup/alma-csv-user-load) — Load users to Alma from CSV files
* [clhennessey/alma-add-home-address-type-to-preferred](https://github.com/clhennessey/alma-add-home-address-type-to-preferred) — Alma home delivery address utility ⭐3
* [clhennessey/alma-change-external-user-notes-from-file](https://github.com/clhennessey/alma-change-external-user-notes-from-file) — Convert Alma user notes from external to internal ⭐3

### E-Resources
* [Alma-Delete-Portfolios-In-Batch](https://github.com/MrJeremyHobbs/Alma-Delete-Portfolios-In-Batch) — Batch delete electronic portfolios in Alma ⭐4
* [alma-e-collection-quick-update](https://github.com/ExLibrisGroup/alma-e-collection-quick-update) — Quickly update E-Collections in Alma

### Printing & Labels
* [SpineOMatic](https://github.com/ExLibrisGroup/SpineOMatic) — Spine label printing for Alma ⭐41
* [alma-print-daemon](https://github.com/ExLibrisGroup/alma-print-daemon) — Listens for and prints letters from Alma print queues ⭐11
* [bis-uni-oldenburg/alma-spine-label-printing](https://github.com/bis-uni-oldenburg/alma-spine-label-printing) — Spine label printing from Alma (PHP)
* [Orbis-Cascade-Alliance/slip-printer](https://github.com/Orbis-Cascade-Alliance/slip-printer) — Institutional slip printer ⭐3

### Sample Applications
* [alma-blacklight](https://github.com/jweisman/alma-blacklight) — Blacklight discovery interface over Alma ⭐13
* [Alma-AWS-Lambda](https://github.com/jweisman/Alma-AWS-Lambda) — AWS Lambda functions for Alma ⭐11
* [alma-apis-rails-vue](https://github.com/jweisman/alma-apis-rails-vue) — Sample app using Alma APIs, Rails, and Vue ⭐5
* [My-Alma-Rails-Library](https://github.com/jweisman/My-Alma-Rails-Library) — Student portal app in Rails based on Alma APIs ⭐5

## Analytics & Reporting

* [ExlTableauWDC](https://github.com/ExLibrisGroup/ExlTableauWDC) — Tableau Web Data Connector for Ex Libris Analytics ⭐4
* [WRLC/interactive-alma-reports](https://github.com/WRLC/interactive-alma-reports) — Interactive reports utilizing Alma APIs
* [rreka/Automating-collections-assessment](https://github.com/rreka/Automating-collections-assessment) — Python programs for automating library e-journal collection assessment ⭐7
* [Orbis-Cascade-Alliance/analytics-101](https://github.com/Orbis-Cascade-Alliance/analytics-101) — Introductory lessons for Alma and Primo Analytics reports

## Integrations

*Integrations between Alma and other systems.*

* [exl-touchnet-connector](https://github.com/ExLibrisGroup/exl-touchnet-connector) — Alma/Primo ↔ TouchNet payment system
* [exl-ezproxy-authenticator](https://github.com/ExLibrisGroup/exl-ezproxy-authenticator) — EZproxy authenticator for Alma ⭐5
* [WRLC/Alma_Physical_Addon](https://github.com/WRLC/Alma_Physical_Addon) — ILLiad Client Addon for physical item requests to Alma
* [GobiChecker](https://github.com/MrJeremyHobbs/GobiChecker) — Validates GOBI requests against Alma holdings
* [Dioscorides/ExLibris-Alma-Primo-Permalink-Grabber](https://github.com/Dioscorides/ExLibris-Alma-Primo-Permalink-Grabber) — Alma/Primo permalink grabber
* [LeidenUniversityLibrary/Alma-Acquisitions-Open-Source](https://github.com/LeidenUniversityLibrary/Alma-Acquisitions-Open-Source) — Display recent acquisitions using Alma Analytics as a source

## Consortia & Organizations

*Consortia and organizations using GitHub to share Alma/Primo configurations, tools, and resources.*

* [ExLibrisGroup](https://github.com/ExLibrisGroup) — Official Ex Libris (119+ repos)
* [WRLC](https://github.com/WRLC) — Washington Research Library Consortium
* [Orbis Cascade Alliance](https://github.com/Orbis-Cascade-Alliance) — Pacific Northwest academic library consortium
* [alliance-pcsg](https://github.com/alliance-pcsg) — Orbis Cascade Alliance Primo Customization Standing Group
* [primousers](https://github.com/primousers) — ELUNA/IGeLU Primo community projects
* [CSU-ULMS](https://github.com/CSU-ULMS) — CSU Unified Library Management System
* [Los-Rios-Libraries](https://github.com/Los-Rios-Libraries) — Los Rios Community College District Libraries
* [wrlc-primo-dev](https://github.com/wrlc-primo-dev) — WRLC Primo development

## Individuals

*People using GitHub to store/share their Alma/Primo configurations, tools, etc.*

* [Josh Weisman](https://github.com/jweisman) — Ex Libris developer; Alma APIs, Blacklight, Cloud Apps
* [Jeremy Hobbs](https://github.com/MrJeremyHobbs) — Alma tools: LazyLists, Book-Be-Gone, RoboReturns, SRU tools
* [Lori Stethers, Wesleyan University](https://github.com/lstethers)
* [David Walker](https://github.com/dswalker) — PHP Alma API client library
* [Colin Bitter](https://github.com/colinbitter) — Primo VE MARC21 normalization rules

## Community

*Community resources, documentation, and discussion.*

* [Ex Libris Developer Network](https://developers.exlibrisgroup.com/) — Official API documentation and developer resources
* [GitHub Topic: ex-libris](https://github.com/topics/ex-libris) — GitHub topic for Ex Libris projects
* [GitHub Topic: exlibris](https://github.com/topics/exlibris) — GitHub topic for ExLibris projects
* [GitHub Topic: alma](https://github.com/topics/alma) — GitHub topic for Alma projects
* [ELUNA](https://el-una.org/) — Ex Libris Users of North America
* [IGeLU](https://igelu.org/) — International Group of Ex Libris Users

---

## Contributing

Contributions welcome! Please open a pull request or issue to add a repo.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
