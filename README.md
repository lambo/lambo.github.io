# Lambert Heller

## Enriching Wikimedia Commons with an open content identifier - a suggestion

## What is Content Identification?

Large media databases such as YouTube and Spotify have been using content identification algorithms for many years. ([https://de.wikipedia.org/wiki/Content_ID](https://de.wikipedia.org/wiki/Content_ID)) These are systems with which content uploaded quickly in the background is checked to see whether it contains content, in whole or in part, that has previously been claimed by a copyright owner as its own content, e.g. as only reusable against payment of a license fee. Content-ID is now able to recognize even small parts of a work fairly well. Some of the components are still reliably recognized even if they are reproduced in a distorted or altered manner.

## Content Identification users and application scenarios today

However, the content ID systems used in industry are proprietary. Exactly how they work is a company secret of the respective platform owners. The results obtained with them cannot be reliably reproduced by third parties. Their use can only be discussed and influenced to a very limited extent by a broader community of affected media users. The platforms they use operate their own registers for rights owners, and these are used by the rights owners to register the "digital DNA" of their works, so that YouTube can, for example, block certain downloads in advance.[^1] Of course, the technology behind Content-ID already has numerous other areas of application, e.g. criminal prosecution authorities use it to automatically locate potential CSAM (Child Sexual Abuse Material) in media collections. Content identification is also used in research.

## Content identification as a tool for everyone - requirements and application examples

For several years, the international standardization organization ISO has been preparing an open, robust, cross-media standard for content identification. ([ISO/CD 24138.2 - Information and documentation — International Standard Content Code](https://www.iso.org/standard/77899.html)) New areas of application are emerging for such an open standard. In the public discussion, examples from the field of creative industries are often mentioned - but also in the field of works in the public domain, diverse and promising application scenarios are conceivable. In the following, three of them are outlined as examples.

### Example 1: Efficient proof of public domain works as a tool for dark archives

A significant problem in the field of historical image collections are images that have long since been digitized in high resolution and made available online with high-quality metadata, but whose access must be restricted (dark archive) or that cannot be marked as public domain because the respective image collection does not does not manage to find reliable proof of public domain with reasonable effort. This could change if there were a data pool in which reproducible, reusable identifiers for public domain images were collected. Based on this data pool, a tool could be developed for the operators of such collections that would allow them to efficiently make parts of their collections more freely accessible, better document them digitally, link them to existing collections such as Wikimedia Commons, etc. Not only the respective collections could benefit significantly from this, but also research and the general public. An actor in the development of such tools could be e.g. NFDI4Culture in Germany ([https://nfdi4culture.de/](https://nfdi4culture.de/)).

### Example 2: Contextual information about public domain works at the point of view

In learning environments, on websites, in digital books and in many other places, "classics" are often shown or heard that invite closer examination - be it passively analytical or creative. However, a wealth of freely available information on these classics is often not intuitively available “within a click”. High-resolution variants, newer and often better digitized versions of the same original, etc. are also missing. With the help of the data pool mentioned above, it would be possible to develop a browser plugin or a smartphone app that would point to such additional information in the respective context and make it accessible.

### Example 3: Register for training data of artificial neural networks

In the discourse on digitality in art today (2023) one topic clearly dominates worldwide, and that is generative artificial intelligence. An ideal that is often discussed here is the transparent registration of the training data on which, for example, large language models (LLM, Large Language Model) or diffusion models (e.g. stable diffusion) are built. With the data pool outlined above, it would be possible to set up a registration service with which designers of large and small artificial neural networks can register their training data. The resulting register would be a unique source for the collaborative development of such networks in the sense of a digital commons, up to the research and development of new applications in the field of Explained Artificial Intelligence (XAI, Explainable AI).

## Implementation with Structured Data on Commons

The above examples assume a data pool in which reproducible, reusable identifiers for public domain images and other media types would be collected. Wikimedia Commons  would be a particularly suitable starting point, since a critical mass of works in the public domain is continuously being collected, described and used here. It would be conceivable, for example, for each new work registered in Commons from a certain level of maturity - metadata is often corrected or supplemented within a relatively short period of time after the creation of a newly added work - to automatically generate a content identifier based on a high-resolution digital copy and comprehensive metadata , and this identifier in a new data field on Structured Data on Commons([https://commons.wikimedia.org/wiki/Commons:Structured_data](https://commons.wikimedia.org/wiki/Commons:Structured_data)) to deposit. ISCC Content Codes ([https://iscc.codes/](https://iscc.codes/)) are used, as they are also the basis for the ongoing standardization at ISO, see also above.

The register mentioned in the third application example could probably be implemented in and with Wikidata.

## The Internet Archive would have the potential to expand the pool of data

The Internet Archive ([https://archive.org/](https://archive.org/)) has crawled and archived freely accessible websites for many years. Among the automatically collected material there will almost inevitably be many works that are machine-readably marked as in the public domain (e.g. on the websites of some museums and art collections), many will also be in Wikimedia Commons, and the intersection between these two sets can only be estimated today. In principle, it would be desirable if the Internet Archive would also use ISCC content codes to identify high-resolution digital copies in its archives (or at least those that are marked as public domain in machine-readable form). Many of the above use cases would also benefit from this extensive pool of data.

## About the author

I am active in an unpaid role on the advisory board of the ISCC since 2020. I am co-author of the original [NFDI4Culture grant proposal, 2020](https://doi.org/10.3897/rio.6.e57036). I’m a Wikimedia [fanboy](https://twitter.com/Lambo/status/1454064183734116353) since… always.

<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     Fitzner, Julia. _Von Digital-Rights-Management zu Content Identification: Neue Ansätze zum Schutz urheberrechtlich geschützter Multimediawerke im Internet._ 1st ed. Nomos Verlagsgesellschaft mbH, 2011. [http://www.jstor.org/stable/j.ctv941v7v](http://www.jstor.org/stable/j.ctv941v7v).
