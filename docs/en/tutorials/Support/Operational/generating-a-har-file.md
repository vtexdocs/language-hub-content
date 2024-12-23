---
title: 'Generating a HAR file for troubleshooting'
id: 15xVlw8nuakk2k6Cao4k2Q
status: PUBLISHED
createdAt: 2018-02-23T13:16:02.404Z
updatedAt: 2019-12-31T15:25:44.314Z
publishedAt: 2019-12-31T15:25:44.314Z
firstPublishedAt: 2018-02-23T14:02:06.722Z
contentType: tutorial
productTeam: Others
author: authors_24
slugEN: generating-a-har-file
locale: en
legacySlug: generating-a-har-file
subcategoryId: 1VvCpaa8NCA6a0MK6W6oWg
---

When looking for solutions to a complex problem, our support team may need to receive additional information about the web requests generated in your browser while the problem occurs.

A useful feature for this is the requests log generated by the browser's developer tools.

Through it you can generate a __HAR__ file, which contains detailed information about each request. Then just send it to our support team.

>⚠️ The HAR file contains sensitive information about your store. Share it only with VTEX support team.

>⚠️ The step-by-step of how to generate a HAR file using **Google Chrome** is below. This is the most recommended way to proceed, but if you want to use other browsers, such as Mozilla Firefox or Microsoft Edge, be sure to check out the correct procedure [here]([https://support.zendesk.com/hc/en-us/articles/204410413-Generating-a-HAR-file-for-troubleshooting).

### Generating the HAR file in Google Chrome

Using Google Chrome, follow the steps below to generate the HAR file.

1. Navigate to the URL where the problem is occurring.
2. Right-click anywhere on the screen and then click __Inspect__.
3. Dev Tools will open, so click the __Network__ tab.![HARfile2](https://images.contentful.com/alneenqid6w5/7vSYRmkjduq6iCaiGgyIo/fd3f3eb23fa57582f8c8f5cd1ac725b5/HARfile2.png)
4. The recording button should be red, which indicates it's enabled. If it's not, click it.![HARfile3](//images.contentful.com/alneenqid6w5/6YnW3ebd1mq2kQsm8uKG2q/97000a534abfabc66931d27ff9cd28b8/HARfile3.png)
5. Check the __Preserve log__ flag.![HARfile5](//images.contentful.com/alneenqid6w5/xQAIiEuHIsaoSCUkSsOEE/e6dc32f580a2f50a5789ae39babfb540/HARfile5.png)
6. Reload the page and repeat the navigation in which the problem occurs.
7. Right-click anywhere within the Network area, and then click __Save as HAR with content__.![HARfile4](//images.contentful.com/alneenqid6w5/hR0VTzzNFmyQc4A4KS02G/b1f15e2131e21b80f5f2c97023cd0a5b/HARfile4.png)

A file with HAR extension, whose name is the address of the page, will be generated.

You can send this file to the VTEX support team, which will make support faster and more efficient.

---

NOTE: In other browsers, such as Mozilla Firefox and Microsoft Edge, the procedure for generating HAR files is similar. However, we recommend using Chrome for this because of the ease of the process.
