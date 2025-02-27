# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on [ ... date you accessed the file ... ]


User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /


## Explanation

The file is used to manage the behavior of automated agents that crawl the website.
It is placed at the root of the site so that when a crawler visits, it knows immediately what is allowed or disallowed.
The first line (beginning with user-agent) indicates that the rules apply to all web crawlers,
meaning every robot that visits the site should follow the rules that follow. The second line instructs all crawlers to wait 10 seconds between successive requests.
"Allow: /" tells crawlers that they are permitted to access every part of the website (the / represents the root directory, including all its subdirectories). "User-agent: SemrushBot"
indicates that the following block applies specifically to the crawler known as SemrushBot. The following line, "Disallow: /", tells SemrushBot that 
it is not allowed to crawl any part of the website.
