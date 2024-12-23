---
title: Welcome to ArticleOS
author: articleos
date: 2024-12-20 16:11:00 +0300
categories: [ArticleOS, Articles]
tags: [articleos]
---

ArticleOS is a web application, developed to make Conference Announcements, and University Presentations. Our motivation for developing ArticleOS comes from that there were no a platform that International Students can find more information a University. Our goal is to be a platform where International Students can find a University List. While we were developing this platform for University Presentations, we thought it would be useful for Conference Announcements, too. Therefore, we included Conference Announcements into this platform.

## Conference Announcements, and University Presentations

ArticleOS does not aim to be a just simple platform to make Conference Advertisement or University Advertisement. Our aim is to make a platform for Students, Researchers to find all the approved information for `Conference Announcements` or `University Presentations`

 {: .filepath} and put it in the `_posts`{: .filepath} of the root directory. Please note that the `EXTENSION`{: .filepath} must be one of `md`{: .filepath} and `markdown`{: .filepath}. If you want to save time of creating files, please consider using the plugin [`Jekyll-Compose`](https://github.com/jekyll/jekyll-compose) to accomplish this.

## Front Matter

Basically, you need to fill the [Front Matter](https://jekyllrb.com/docs/front-matter/) as below at the top of the post:

```yaml
---
title: TITLE
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [TAG]     # TAG names should always be lowercase
---
```

> The posts' _layout_ has been set to `post` by default, so there is no need to add the variable _layout_ in the Front Matter block.
{: .prompt-tip }

### Timezone of Date

To accurately record the release date of a post, you should not only set up the `timezone` of `_config.yml`{: .filepath} but also provide the post's timezone in variable `date` of its Front Matter block. Format: `+/-TTTT`, e.g. `+0800`.

### Categories and Tags

The `categories` of each post are designed to contain up to two elements, and the number of elements in `tags` can be zero to infinity. For instance:

```yaml
---
categories: [Animal, Insect]
tags: [bee]
---
```

### Author Information