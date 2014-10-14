rorcid
======

[![Build Status](https://api.travis-ci.org/ropensci/rorcid.png)](https://travis-ci.org/ropensci/rorcid)
[![Build status](https://ci.appveyor.com/api/projects/status/29hanha8jfe4uen8/branch/master?svg=true)](https://ci.appveyor.com/project/sckott/rorcid/branch/master)

`rorcid` is an R programmatic interface to the Orcid public API. `rorcid` is not a product developed or distributed by ORCID®.

## Installation

```R
install.packages("devtools")
devtools::install_github("ropensci/rorcid")
library('rorcid')
```

## Information

+ [Orcid API docs](http://support.orcid.org/knowledgebase/articles/116874-orcid-api-guide)

+ `rorcid` is part of the rOpenSci project, [click to find out more](http://ropensci.org/)

+ Hopefully various web services will start integrating Orcid ID's into their API services so that e.g., you could disambiguate authors with similar names from the [Mendeley API](URL). We will keep a list of them here:
	+ [ScienceCard](http://sciencecard.org)
		+ An example call: [http://sciencecard.org/api/v3/users/0000-0002-1642-628X?info=summary](http://sciencecard.org/api/v3/users/0000-0002-1642-628X?info=summary)

## Quick start

> Coming soon

## Meta

* Please [report any issues or bugs](https://github.com/ropensci/rorcid/issues).
* License: MIT
* This package is part of the [rOpenSci](http://ropensci.org/packages) project.
* Get citation information for `rorcid` in R doing `citation(package = 'rorcid')`

[![ropensci](http://ropensci.org/public_images/github_footer.png)](http://ropensci.org)
