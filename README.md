# eml-syntax
EML Syntax for Sublime Text 3. Forked &amp; Updated from https://github.com/mariozaizar/eml-tmLanguage

### Description

Leveraged the [PackageDev Automatic Updater](https://github.com/SublimeText/PackageDev/wiki/Syntax-Definitions#converting-a-textmate-to-a-sublime-text-syntax-definition) for `.tm-Language` to `.sublime-syntax` conversion.

Added:
 * Distinct format for Timestamps, as per [RFC 5322 Sec 3.3](https://tools.ietf.org/html/rfc5322#section-3.3)
* Distinct format for `Received` Trace fields.
* Distinct format for `X-` extensible headers.
* Leveraging the ST3 ability, push HTML Syntax for HTML message content.


### References

* LINKS: 
  * https://github.com/SublimeText/PackageDev/wiki/Syntax-Definitions#converting-a-textmate-to-a-sublime-text-syntax-definition
  * https://tools.ietf.org/html/rfc5322#section-3.3