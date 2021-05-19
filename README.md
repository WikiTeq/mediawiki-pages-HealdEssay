# HEALD Essay

Provides a collection of wiki pages for easy inclusion of Essay fields and semantics in Mediawiki projects (HEALD wiki).

# Requirements

* MediaWiki 1.30+
* SemanticMediaWiki
* PageForms
* ParserFunctions (`$wgPFEnableStringFunctions = true;`)
* PagePort or PageExchange

# Setup

## via PagePort 

* download the repository
* run `php extensions/PagePort/maintenance/importPages.php --source ~/mediawiki-pages-HealdEssay`

## via PageExchange

* Add the following line to your LocalSettings.php `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/WikiTeq/mediawiki-pages-HealdEssay/master/page-exchange.json';`
* Navigate to `Special:Packages` and install the package
