---
title: 'AB Testing: why is it not working? (Google Analytics)'
id: frequentlyAskedQuestions_629
status: PUBLISHED
createdAt: 2017-04-27T22:31:14.775Z
updatedAt: 2019-12-31T14:24:07.364Z
publishedAt: 2019-12-31T14:24:07.364Z
firstPublishedAt: 2017-04-27T23:02:25.985Z
contentType: frequentlyAskedQuestion
productTeam: Others
author: authors_84
slugEN: ab-testing-why-is-it-not-working-google-analytics
locale: en
legacySlug: ab-testing-why-is-it-not-working-google-analytics
---

Usually, this situation happens because the store owner is not able to save the script generated by Analytics inside the Template.

To solve this problem, just follow the steps below:

1. Create a contentPlaceHolder inside the Template.
2. On the page on which AB Testing is being applied, create an HTML-type control and save the script.

This way, AB Testing will be successful.

See below the screens with examples of the steps:

__Control Screen__:
![](https://images.contentful.com/alneenqid6w5/3GIGsJXbo4KAMikCqesM6s/e8231671043f3ce763c8faf87718d6d7/testeAB-controle1-300x138.png)

__Script Screen__:
![](//images.contentful.com/alneenqid6w5/7gUgGNnvlmcQyiW4A0A6ao/dac8e58e0931686de3e9e4ae46c66afa/testeAB-script-300x148.png)

__Template Screen__:
![](//images.contentful.com/alneenqid6w5/4u6uQHYOPuw6Ws8CYKCISo/d04c5fbcc08a5de8a05a242ef76e7ecf/testeAB-template-300x216.png)
