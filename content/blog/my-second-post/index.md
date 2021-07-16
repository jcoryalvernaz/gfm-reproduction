---
title: My Second Post!
date: "2015-05-06T23:46:37.121Z"
---

Wow! I love blogging so much already.

|     |
|-----------|--------------------------------------------------------------
| title     | Post or page title (article headline).
| link      | Specifies the [Parse.ly canonical URL](/help/integration/faq-metadata#the-parsely-canonical-url) for post or page. For [page groups](/help/integration/multipage-articles), like galleries, it should always point to the main page. For accurate data, canonical urls specified in other metadata tags (such as `<link rel="canonical">` and `<meta property="og:url">` tags) must match, resolve, or redirect to this url. For more information, please refer to our [documentation on shares integration](https://www.parse.ly/help/kb/shares-integration/).
| image\_url| URL of the image associated with the post/page.
| type      | Page type - "post", "frontpage" or "sectionpage"
| post\_id  | String that uniquely identifies this post. Unless otherwise instructed by Parse.ly support, should be omitted in favor of `link`.
| pub\_date | Publication date, as ISO 8601 UTC timezone string.
| section   | Section the page belongs to (e.g. "Politics").
| authors   | List of post authors.
| tags      | List of tags associated with this post.
| metadata  | Arbitrary data to attach to post. Must be a valid JSON string. See [documentation about custom metadata](/help/api/custom-metadata).

|           |
|-----------------|----------------------------------------------
| type            | One of `posts`, `authors`, `sections`, `tags`, `referrers`, `channels`, `campaigns`, `segments`

Did you know that "despite its name, salted duck eggs can also be made from
chicken eggs, though the taste and texture will be somewhat different, and the
egg yolk will be less rich."?
([Wikipedia Link](https://en.wikipedia.org/wiki/Salted_duck_egg))

Yeah, I didn't either.
