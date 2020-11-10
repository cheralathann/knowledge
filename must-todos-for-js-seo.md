## 5 must-dos to make your JS app search engine friendly

* Think URLs
    
    --- Links ---
    - use links to aid discovery
    - use links to express relationship
    - Avoid onclick and imperative navigation

    --- robot.txt ---
    - Blacklist url patterns
    - use to exclude test and archive site from index
    - use carefully
    - Don't block javascript, assets and data API URLs

    --- sitemap.xml ---
    - Guidance for search crawlers
    - Doesn't guarantee indexing
    - at minimum add entries for static urls and routes

*  Pick your SEO Strategy
    - It is good to make Server Side SEO
    * Factors to consider for your SEO Strategy
       - Know your audience
       - How much time, money and effort can your invest (Resources)
       - Extras

* Get to know your tools
  - Search console
  - Google analytics
  - Segment

* Being successful without servers
   *  3 important consideration
      - Polyfills for legacy browser
      - HTTP 500 Internal server error 
         - Plans for error in production
         - Setup logging & alerts
         - Consider adding no index meta tag from JS error handler
      - HTTP 404 not found
         - Crawlers will come across broken links
         - use no index meta tag to exclude from index
         - watch out for soft 404 errors
         - Don't make your 404 pages a crawler honey pot

* Sustaining your success
   * Monitoring (helps us to see trends)
    - Review search console and analytics regularly
    - Experiments and analyze
    - use data to drive future improvements
   * Logging (Provides insights)
    - setup remote error logging
    - make sure you capture useragent info
   * Alerting
    -  alerting enables quick response
