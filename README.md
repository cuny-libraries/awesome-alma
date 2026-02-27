# awesome-alma

A curated list of awesome Ex Libris Alma & Primo VE repos, tools, and resources.

Inspired by [awesome lists](https://github.com/sindresorhus/awesome). Contributions welcome!

---

## Contents

- [Official Ex Libris](#official-ex-libris)
- [API Client Libraries](#api-client-libraries)
- [Primo Development & Customization](#primo-development--customization)
- [Primo Explore Plugins](#primo-explore-plugins)
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
* [Primo.Show-PNX-IDs-Bookmarklet](https://github.com/ExLibrisGroup/Primo.Show-PNX-IDs-Bookmarklet) — Bookmarklet to show PNX IDs in Primo ⭐5
* [ExlTableauWDC](https://github.com/ExLibrisGroup/ExlTableauWDC) — Tableau Web Data Connector for Ex Libris Analytics ⭐4
* [Alma.Converters](https://github.com/ExLibrisGroup/Alma.Converters) — Converters for Alma integrations ⭐4
* [Discovery-Showcase](https://github.com/ExLibrisGroup/Discovery-Showcase) — Discovery Showcase examples ⭐4
* [alma-csv-user-load](https://github.com/ExLibrisGroup/alma-csv-user-load) — Load users to Alma from CSV files ⭐2
* [alma-receive-serials](https://github.com/ExLibrisGroup/alma-receive-serials) — App to efficiently receive new serials items in Alma ⭐2
* [alma-e-collection-quick-update](https://github.com/ExLibrisGroup/alma-e-collection-quick-update) — Quickly update E-Collections in Alma ⭐2
* [cloudapp-tutorials](https://github.com/ExLibrisGroup/cloudapp-tutorials) — Tutorials for Ex Libris Cloud Apps ⭐1
* [exl-touchnet-connector](https://github.com/ExLibrisGroup/exl-touchnet-connector) — Connector between Alma/Primo and the TouchNet payment system ⭐1
* [MARC-2-BF2](https://github.com/ExLibrisGroup/MARC-2-BF2) — Crosswalk from MARC21 to BIBFRAME2 ⭐1
* [alma-invoice-line-tax-calculator](https://github.com/ExLibrisGroup/alma-invoice-line-tax-calculator) — Invoice Line Tax Calculator Cloud App ⭐1
* [print-bib-record](https://github.com/ExLibrisGroup/print-bib-record) — Cloud App for printing BIB records from Alma ⭐1
* [Archive-It-Open-Search-API-Primo-widget](https://github.com/ExLibrisGroup/Archive-It-Open-Search-API-Primo-widget) — Primo search widget for Archive-It ⭐1

## API Client Libraries

*Client libraries and wrappers for the Alma REST APIs in various languages.*

### Python
* [almapipy](https://github.com/UCDavisLibrary/almapipy) — Python wrapper for the Alma API (UC Davis)
* [pyalma](https://github.com/thegetty/pyalma) — Simple Python client for Alma BIBs API (Getty) ⭐15
* [alma-batch](https://github.com/gwu-libraries/alma-batch) — Asynchronous Python for Alma APIs, supports pandas DataFrames (GWU Libraries) ⭐9
* [nlnzcollservices/Alma-tools](https://github.com/nlnzcollservices/Alma-tools) — Python tools for Alma REST API (National Library of NZ) ⭐3
* [Alma-Helper](https://github.com/MrJeremyHobbs/Alma-Helper) — Rudimentary Python library for Alma APIs ⭐2
* [exl_alma_tools](https://github.com/KoroteevaS/exl_alma_tools) — Middleware between Alma API and Python pipelines

### Ruby
* [exlibris-primo](https://github.com/scotdalton/exlibris-primo) — Ruby library for Ex Libris Primo ⭐18
* [alma_rb](https://github.com/tulibraries/alma_rb) — Ruby client for Alma Web Services (Temple University) ⭐9
* [alma_api](https://github.com/ubpb/alma_api) — Ruby client library for Alma REST APIs ⭐2
* [BerkeleyLibrary/alma](https://github.com/BerkeleyLibrary/alma) — Alma/Primo utilities for UC Berkeley Library ⭐2
* [almarestapi-ruby-lib](https://github.com/jweisman/almarestapi-ruby-lib) — Ruby library for Alma REST APIs ⭐2

### JavaScript / Node.js
* [primo-explore-dom](https://github.com/mehmetc/primo-explore-dom) — Simple Domain Object Model for the Primo New UI ⭐23
* [alma-utils](https://github.com/UCDavisLibrary/alma-utils) — JavaScript library for Alma API (UC Davis) ⭐2
* [almarestapi-node-lib](https://github.com/jweisman/almarestapi-node-lib) — Node.js library for Alma REST APIs ⭐3
* [simple-node-alma-apis](https://github.com/jweisman/simple-node-alma-apis) — Simple Node.js examples for Alma APIs ⭐4

### PHP
* [dswalker/alma-api](https://github.com/dswalker/alma-api) — PHP client library for Alma and Primo web services ⭐16

### Perl
* [spotrick/AlmaWS](https://github.com/spotrick/AlmaWS) — Perl modules for Alma web services ⭐5

### C#
* [reeset/alma_api_library](https://github.com/reeset/alma_api_library) — MarcEdit Alma API Library Code ⭐4

## Primo Development & Customization

*Tools and customization packages for Primo Classic and Primo VE.*

### Development Tools
* [primo-explore-devenv](https://github.com/ExLibrisGroup/primo-explore-devenv) — Official Primo UI dev environment ⭐118
* [primo-explore-dom](https://github.com/mehmetc/primo-explore-dom) — Simple Domain Object Model for the Primo New UI ⭐23
* [primousers/primostudio](https://github.com/primousers/primostudio) — Repository of Primo-explore projects from ELUNA/IGeLU communities ⭐11
* [dpuwebservices/localDev-primoVE](https://github.com/dpuwebservices/localDev-primoVE) — Local development environment for Primo VE views

### Institutional Customization Packages
* [vculibraries/alma-primo-customizations](https://github.com/vculibraries/alma-primo-customizations) — CSS/JS customizations for Alma and Primo (VCU) ⭐13
* [alliance-pcsg/ve-central-package](https://github.com/alliance-pcsg/ve-central-package) — Central Package of the Orbis Cascade Alliance for Primo VE ⭐13
* [kb-dk/primo-explore-rex](https://github.com/kb-dk/primo-explore-rex) — Primo customization package (Royal Danish Library, archived) ⭐13
* [rgilmour70/ic-primo-ve](https://github.com/rgilmour70/ic-primo-ve) — Primo VE customization files (Ithaca College) ⭐10
* [UCLALibrary/primo_ve](https://github.com/UCLALibrary/primo_ve) — UCLA Library Primo VE customizations ⭐8
* [alliance-pcsg/ve-customizations](https://github.com/alliance-pcsg/ve-customizations) — Additional Primo VE customizations (Orbis Cascade Alliance) ⭐6
* [kb-dk/KB-Primo-VE](https://github.com/kb-dk/KB-Primo-VE) — Royal Danish Library Primo VE customization ⭐6
* [Los-Rios-Libraries/Primo-VE-Views](https://github.com/Los-Rios-Libraries/Primo-VE-Views) — Primo VE customization package (Los Rios CCD)
* [Brandeis-Library/primo-ve-customization-package](https://github.com/Brandeis-Library/primo-ve-customization-package) — Primo VE customization (Brandeis)
* [HSG-Library/hsg-primo-view](https://github.com/HSG-Library/hsg-primo-view) — HSG Swisscovery customization package
* [cu-library/primo-customization-package](https://github.com/cu-library/primo-customization-package) — Primo/Omni customization (Carleton University)
* [LincolnUniLTL/primo](https://github.com/LincolnUniLTL/primo) — JavaScript and CSS customizations for hosted Primo (Lincoln University)

## Primo Explore Plugins

*Reusable plugins and add-ons for Primo Explore / Primo VE.*

* [LeidenUniversityLibrary/Library-Search-Plugin-Public](https://github.com/LeidenUniversityLibrary/Library-Search-Plugin-Public) — Browser plugin to search library catalog, Google Scholar, WorldCat from anywhere ⭐26
* [UMNLibraries/primo-explore-hathitrust-availability](https://github.com/UMNLibraries/primo-explore-hathitrust-availability) — Adds HathiTrust availability for public domain content ⭐24
* [alliance-pcsg/primo-explore-custom-actions](https://github.com/alliance-pcsg/primo-explore-custom-actions) — Easily add custom actions to Primo's actions menu ⭐15
* [alliance-pcsg/primo-explore-my-ill](https://github.com/alliance-pcsg/primo-explore-my-ill) — Load ILLiad requests into Primo "My Account" ⭐10
* [SarahZum/primo-explore-custom-no-results](https://github.com/SarahZum/primo-explore-custom-no-results) — Custom text and options for no-result scenarios ⭐10
* [csudhlib/primo-explore-google-analytics](https://github.com/csudhlib/primo-explore-google-analytics) — Adds Google Analytics to Primo ⭐9
* [NYULibraries/primo-explore-google-analytics](https://github.com/NYULibraries/primo-explore-google-analytics) — Google Analytics for Primo NUI (archived) ⭐8
* [primo-explore-lod-author-card](https://github.com/jweisman/primo-explore-lod-author-card) — Linked Open Data Author Card for Primo Explore ⭐7
* [alliance-pcsg/primo-explore-report-problem](https://github.com/alliance-pcsg/primo-explore-report-problem) — Adds a warning banner to item detail views ⭐6
* [primo-explore-libraryh3lp-widget](https://github.com/NYULibraries/primo-explore-libraryh3lp-widget) — LibraryH3lp chat widget for Primo (archived) ⭐5
* [jpdenzer/Primo-VE-ZoteroBib-Add-On](https://github.com/jpdenzer/Primo-VE-ZoteroBib-Add-On) — ZoteroBib citation manager add-on for Primo VE ⭐5
* [alliance-pcsg/primo-explore-resource-icons](https://github.com/alliance-pcsg/primo-explore-resource-icons) — Resource icons from the Noun Project for search results ⭐5
* [primo-explore-course-reserves](https://github.com/alliance-pcsg/primo-explore-course-reserves) — Course reserves module using Alma API ⭐4
* [alliance-pcsg/primo-explore-external-search](https://github.com/alliance-pcsg/primo-explore-external-search) — Facet options to transfer searches to external targets ⭐4
* [alliance-pcsg/primo-explore-library-hud](https://github.com/alliance-pcsg/primo-explore-library-hud) — Heads-up display component for Primo Explore ⭐4
* [alliance-pcsg/primo-explore-not-on-shelf](https://github.com/alliance-pcsg/primo-explore-not-on-shelf) — Links to external forms with item information ⭐4
* [alliance-pcsg/primo-explore-toggle-institutions](https://github.com/alliance-pcsg/primo-explore-toggle-institutions) — Toggles visibility of other institutions owning items ⭐3
* [alliance-pcsg/primo-explore-oadoi-link](https://github.com/alliance-pcsg/primo-explore-oadoi-link) — Links to Open Access content for articles ⭐3
* [alliance-pcsg/primo-explore-favorites-warning](https://github.com/alliance-pcsg/primo-explore-favorites-warning) — Warns about login requirements for permanent favorites ⭐3
* [Primo-Book-Cover-Carousel](https://github.com/wadeguidry/Primo-Book-Cover-Carousel) — Rotating carousel of book covers from Alma Analytics

## Primo VE Normalization & Discovery

*Normalization rules and discovery enhancements.*

* [primousers/primo-ve-norm](https://github.com/primousers/primo-ve-norm) — Community Primo VE XML normalization rules ⭐29
* [Orbis-Cascade-Alliance/ve-norm-rules](https://github.com/Orbis-Cascade-Alliance/ve-norm-rules) — Alliance VE normalization rules ⭐9
* [colinbitter/Primo-VE-MARC21-Normalization-Rules](https://github.com/colinbitter/Primo-VE-MARC21-Normalization-Rules) — Customized MARC21 normalization rules for Primo VE ⭐7
* [llowery/orbis-nrsg-ve-normrules](https://github.com/llowery/orbis-nrsg-ve-normrules) — Normalization rules from the Orbis Cascade Alliance ⭐6
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
* [LynnAUhlman/AlmaLetters](https://github.com/LynnAUhlman/AlmaLetters) — Alma letter XSLT templates ⭐2
* [cuny-libraries/alma-letters](https://github.com/cuny-libraries/alma-letters) — Alma letter templates (CUNY) ⭐2
* [Orbis-Cascade-Alliance/slip-templates](https://github.com/Orbis-Cascade-Alliance/slip-templates) — Alma letter templates for local and Summit pick slips

## Cloud Apps

*Alma Cloud Apps for extending functionality.*

* [spineomatic-cloudapp](https://github.com/ExLibrisGroup/spineomatic-cloudapp) — Cloud App version of SpineOMatic ⭐8
* [HSG-Library/alma-copy-user-roles](https://github.com/HSG-Library/alma-copy-user-roles) — Cloud App to copy roles between users ⭐4
* [alliance-pcsg/orbis-label-printer](https://github.com/alliance-pcsg/orbis-label-printer) — Cloud App to print spine labels from Alma ⭐2
* [Swiss-Library-Service-Platform/slsp-cloudapps-resources](https://github.com/Swiss-Library-Service-Platform/slsp-cloudapps-resources) — Resources and examples for developing Alma Cloud Apps (SLSP) ⭐2
* [duke-libraries/dsc-alma-cloudapp](https://github.com/duke-libraries/dsc-alma-cloudapp) — Cloud App for the Data Service Center (Duke) ⭐2
* [TuftsUniversity/tufts-alma-cloudapp-citation-loader](https://github.com/TuftsUniversity/tufts-alma-cloudapp-citation-loader) — Create citations and reading lists via Excel upload ⭐1
* [bediniupi/alma-print-loan-slips-cloudapp](https://github.com/bediniupi/alma-print-loan-slips-cloudapp) — Cloud App to print loan slips ⭐1
* [ExLibrisGroup/cloudapp-tutorials](https://github.com/ExLibrisGroup/cloudapp-tutorials) — Official Cloud App tutorials ⭐1
* [HSG-Library/alma-bib-hierarchy](https://github.com/HSG-Library/alma-bib-hierarchy) — Cloud App to display bibliographic hierarchies in Alma

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
* [AlmaInventory](https://github.com/WRLC/AlmaInventory) — Inventory tool using Alma Bib API (WRLC) ⭐2
* [Alma-Hours-Widget](https://github.com/pdxlibrary/Alma-Hours-Widget) — Dynamic HTML hours widget using the Alma Hours API ⭐13
* [rgilmour70/almacal](https://github.com/rgilmour70/almacal) — Library hours calendar using the Alma API ⭐1

### User Management
* [alma-csv-user-load](https://github.com/ExLibrisGroup/alma-csv-user-load) — Load users to Alma from CSV files ⭐2
* [clhennessey/alma-add-home-address-type-to-preferred](https://github.com/clhennessey/alma-add-home-address-type-to-preferred) — Alma home delivery address utility ⭐3
* [clhennessey/alma-change-external-user-notes-from-file](https://github.com/clhennessey/alma-change-external-user-notes-from-file) — Convert Alma user notes from external to internal ⭐3

### E-Resources
* [Alma-Delete-Portfolios-In-Batch](https://github.com/MrJeremyHobbs/Alma-Delete-Portfolios-In-Batch) — Batch delete electronic portfolios in Alma ⭐4
* [alma-e-collection-quick-update](https://github.com/ExLibrisGroup/alma-e-collection-quick-update) — Quickly update E-Collections in Alma ⭐2

### Printing & Labels
* [SpineOMatic](https://github.com/ExLibrisGroup/SpineOMatic) — Spine label printing for Alma ⭐41
* [alma-print-daemon](https://github.com/ExLibrisGroup/alma-print-daemon) — Listens for and prints letters from Alma print queues ⭐11
* [bis-uni-oldenburg/alma-spine-label-printing](https://github.com/bis-uni-oldenburg/alma-spine-label-printing) — Spine label printing from Alma (PHP) ⭐2
* [Orbis-Cascade-Alliance/slip-printer](https://github.com/Orbis-Cascade-Alliance/slip-printer) — Institutional slip printer ⭐3

### Acquisitions & Finance
* [ALMA-Invoices-Update-Status-Paid](https://github.com/MrJeremyHobbs/ALMA-Invoices-Update-Status-Paid) — Invoice status management via Alma APIs ⭐2
* [alma-invoice-line-tax-calculator](https://github.com/ExLibrisGroup/alma-invoice-line-tax-calculator) — Invoice Line Tax Calculator Cloud App ⭐1
* [GobiChecker](https://github.com/MrJeremyHobbs/GobiChecker) — Validates GOBI requests against Alma holdings ⭐2
* [ramerrick/ExLibris-Alma-bulk-fine-waive](https://github.com/ramerrick/ExLibris-Alma-bulk-fine-waive) — Waives fines via Alma API using Alma Analytics lists ⭐1

### Digital & Viewers
* [Alma-Digital-Uploader](https://github.com/jweisman/Alma-Digital-Uploader) — File upload tool for Alma Digital ⭐2
* [Alma-Digital-Viewers](https://github.com/jweisman/Alma-Digital-Viewers) — Internet Archive BookReader integration for Alma ⭐2

### Sample Applications
* [alma-blacklight](https://github.com/jweisman/alma-blacklight) — Blacklight discovery interface over Alma ⭐13
* [Alma-AWS-Lambda](https://github.com/jweisman/Alma-AWS-Lambda) — AWS Lambda functions for Alma ⭐11
* [ELUNA-2019-Dev-Days-Alma-Course](https://github.com/MrJeremyHobbs/ELUNA-2019-Dev-Days-Alma-Course) — Code resources for ELUNA 2019 Developers Day Alma Workshop ⭐10
* [alma-apis-rails-vue](https://github.com/jweisman/alma-apis-rails-vue) — Sample app using Alma APIs, Rails, and Vue ⭐5
* [My-Alma-Rails-Library](https://github.com/jweisman/My-Alma-Rails-Library) — Student portal app in Rails based on Alma APIs ⭐5
* [Renouvaud/apps](https://github.com/Renouvaud/apps) — Homemade tools built on Alma APIs ⭐1

## Analytics & Reporting

* [JayHartzell/alma_citation_inventory_analytics_join](https://github.com/JayHartzell/alma_citation_inventory_analytics_join) — SQL for joins between course reserves and items in Alma Analytics ⭐8
* [rreka/Automating-collections-assessment](https://github.com/rreka/Automating-collections-assessment) — Python programs for automating library e-journal collection assessment ⭐7
* [ExlTableauWDC](https://github.com/ExLibrisGroup/ExlTableauWDC) — Tableau Web Data Connector for Ex Libris Analytics ⭐4
* [WRLC/interactive-alma-reports](https://github.com/WRLC/interactive-alma-reports) — Interactive reports utilizing Alma APIs ⭐2
* [TuftsUniversity/high-usage-library-stats-alma-api](https://github.com/TuftsUniversity/high-usage-library-stats-alma-api) — High-usage library stats via Alma API ⭐2
* [LeidenUniversityLibrary/Alma-Acquisitions-Open-Source](https://github.com/LeidenUniversityLibrary/Alma-Acquisitions-Open-Source) — Display recent acquisitions using Alma Analytics as a source ⭐2
* [Orbis-Cascade-Alliance/analytics-101](https://github.com/Orbis-Cascade-Alliance/analytics-101) — Introductory lessons for Alma and Primo Analytics reports

## Integrations

*Integrations between Alma and other systems.*

* [vculibraries/alma-ncip](https://github.com/vculibraries/alma-ncip) — Plugin to integrate Alma and ILLiad client using NCIP ⭐14
* [exl-touchnet-connector](https://github.com/ExLibrisGroup/exl-touchnet-connector) — Alma/Primo ↔ TouchNet payment system ⭐1
* [exl-ezproxy-authenticator](https://github.com/ExLibrisGroup/exl-ezproxy-authenticator) — EZproxy authenticator for Alma ⭐5
* [WRLC/Alma_Physical_Addon](https://github.com/WRLC/Alma_Physical_Addon) — ILLiad Client Addon for physical item requests to Alma ⭐1
* [grantj-re3/FlindersTheses-alma2equella](https://github.com/grantj-re3/FlindersTheses-alma2equella) — Scripts for migrating digitized theses from Alma to Equella ⭐1
* [Dioscorides/ExLibris-Alma-Primo-Permalink-Grabber](https://github.com/Dioscorides/ExLibris-Alma-Primo-Permalink-Grabber) — Alma/Primo permalink grabber
* [lukaslerche/bookwaves](https://github.com/lukaslerche/bookwaves) — Cloud-based RFID circulation, tagging, and gate monitoring for libraries ⭐1

## Consortia & Organizations

*Consortia and organizations using GitHub to share Alma/Primo configurations, tools, and resources.*

* [ExLibrisGroup](https://github.com/ExLibrisGroup) — Official Ex Libris (119+ repos)
* [WRLC](https://github.com/WRLC) — Washington Research Library Consortium
* [Orbis Cascade Alliance](https://github.com/Orbis-Cascade-Alliance) — Pacific Northwest academic library consortium
* [alliance-pcsg](https://github.com/alliance-pcsg) — Orbis Cascade Alliance Primo Customization Standing Group (25+ repos)
* [primousers](https://github.com/primousers) — ELUNA/IGeLU Primo community projects
* [Swiss-Library-Service-Platform](https://github.com/Swiss-Library-Service-Platform) — SLSP Cloud App resources
* [CSU-ULMS](https://github.com/CSU-ULMS) — CSU Unified Library Management System
* [Los-Rios-Libraries](https://github.com/Los-Rios-Libraries) — Los Rios Community College District Libraries
* [wrlc-primo-dev](https://github.com/wrlc-primo-dev) — WRLC Primo development

## Individuals

*People using GitHub to store/share their Alma/Primo configurations, tools, etc.*

* [Josh Weisman](https://github.com/jweisman) — Ex Libris developer; Alma APIs, Blacklight, AWS Lambda, Cloud Apps
* [Jeremy Hobbs](https://github.com/MrJeremyHobbs) — Alma tools: LazyLists, Book-Be-Gone, RoboReturns, SRU tools
* [Lori Stethers, Wesleyan University](https://github.com/lstethers)
* [David Walker](https://github.com/dswalker) — PHP Alma API client library
* [Colin Bitter](https://github.com/colinbitter) — Primo VE MARC21 normalization rules
* [Mehmet Celik](https://github.com/mehmetc) — primo-explore-dom

## Community

*Community resources, documentation, and discussion.*

* [Ex Libris Developer Network](https://developers.exlibrisgroup.com/) — Official API documentation and developer resources
* [Primo Open Discovery Framework](https://developers.exlibrisgroup.com/primo/odf/) — ODF documentation for Primo customization
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
