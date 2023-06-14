---
title: 'Setting up product comparison'
id: tutorials_236
status: PUBLISHED
createdAt: 2017-04-27T22:13:10.537Z
updatedAt: 2021-04-13T18:46:45.472Z
publishedAt: 2021-04-13T18:46:45.472Z
firstPublishedAt: 2017-04-27T23:03:10.483Z
contentType: tutorial
productTeam: Marketing & Merchandising
author: authors_3
slug: setting-up-product-comparison
legacySlug: setting-up-product-comparison
subcategory: pwxWmUu7T222QyuGogs68
---

Product comparison is a native feature of the VTEX platform and consists displaying, side by side, details and specifications of previously selected products. 

That is, if the feature is correctly set up, the user can easily compare products of the store and view the differences in their specifications in a simple way.

We can divide this feature in two parts::

1. **Comparison Page**: Where the user will view the comparison of products selected in the window shop.
2. **Window display**: Where the user will select the products to be compared.

<div class = "alert alert-warning">
  <p>This feature can't be used on the website's home page.</p>
</div>

## Setting up

Firstly, we should set up the **Comparison Page**.

1. **[Create a shelf template](http://help.vtex.com/en/faq/how-to-create-a-shelf-template):** In **CMS** > **Layout** (/admin/a/), create a shelf template. This shelf template will represent each product on the comparison page. In this template, you can use all controls available for shelves.
2. **[Create a page template](http://help.vtex.com/en/faq/how-to-create-a-page-template):** In **CMS** > **Layout** create a page template and use the ProductComparison control related to the shelf template created in the previous item. This control is largely responsible for the display of the comparison page. This will position each product side by side for better viewing of its specifications. Example of control application: `<vtex.cmc:ProductComparison ShelfLayoutId="12343216-4c8e-4cd5-bcd7-e3b062681f2a"/>`
3. **Create a folder named “Compare”:** In **CMS** > **Layout** > **CMS** Folder > **Sites and channels** > **{Name of the desired website}** > **/ Folder** > **New folder** , create a folder with the name “Compare”. The link generated by the shop window control refers to this folder and therefore its existence is crucial, as well as all items of this post.
4. **Create a standard layout:** On the “Compare” folder created in the previous item, create a standard layout by clicking on **New Layout** and relate it to the template of the page created in item 2 in the **Template** field.

After the Comparison Page is set up, we need to set up the **Shop window** so that the products can be displayed with the compare option (checkbox). This setup is quite simple and comprises only one step:

1. **Set up each Shelf Template you wish:** In the shelf templates you want, include the control  `$product.Compare`. This control will display a checkbox that enables the users to choose the products they want to compare. Additionally, the control will display in the header and footer of the product list the link “Compare”, which will be used by the users after selection and will redirect them to the “Compare” folder.

Done! The feature is enabled for your website.

Important Information: Comparison can be made for four products at a time.