# Article Tools

## Dependencies

* Reeadability temrinal: https://github.com/thavelick/readability-terminal
* Calibre: https://calibre-ebook.com/
* The unix `mail` command configured to send mail (I use the archlinux package `mstmp`)
## Article collection

This takes a file with a list of article urls and:
 * Downloads each aticle
 * Formats it nicely using readabilitiy-terminal
 * Converts all of the articles to a mobi ebook, with a nice table of contents 
   pointing to each article
 * Emails to a kindle email address 


Usage:

```
FROM_EMAIL=tristan@havelick.com KINDLE_EMAIL=youname_0f0f0f@kindle.com ./article-collector articles-list
```

