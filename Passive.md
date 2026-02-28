## Passive Reconnaissance

Passive reconnaissance is information gathering that will not typically leave artifacts/logs or using public services like WHOIS, TheirStack, and even just Google.

### WHOIS

When registering a domain, registrars will almost always require identification. Though it is now also common for them to offer anonymization, this is still often a valuable and extensive source of information. Anyone can see it with the WHOIS tool like so:
```
whois google.com
```

### Google

Google is often an often underlooked but powerful index for this phase. Google Maps entries alone intentionally condense physical addresses, websites, contact info, and hours in one place. Further, using [search operators](https://www.googleguide.com/advanced_operators_reference.html#) can yield results not normally present in search results or intended for public view. Here is an example of using Google search operators to find more specific content on a site:
```
inurl:nist.gov filetype:pdf
```

### TheirStack

[TheirStack](https://www.theirstack.com/) is a service that indexes job listings with the technologies they are hiring for. This means TheirStack has an evolving [dataset](https://www.theirstack.com/technographics-dataset/) of what technologies a company is using.

### Censys

[Censys](https://platform.censys.io/home) is a service that constantly scans the internet for live hosts and stores the results for query. Some of the filters can be incredibly powerful such as:
```
host.services.software.vendor = "crushftp"
host.services.vulns.metrics.cvss_v30.score >= "6" or web.vulns.metrics.cvss_v30.score >= "6"
```

### OSINT Framework

The [OSINT Framwork](https://osintframework.com/) is a collection of tools for Open Source INTelligence gathering. It is a very solid resource and can provide a more organised workflow for this phase.

### Maltego

[Maltego](https://maltego.com) cites itself as a platform for OSINT and investigations. It is an incredibly powerful graphical client for investigating entities like individuals and businesses. It also offers sentiment analysis for social media and other online traffic to potentially identify early warnings for attacks.
