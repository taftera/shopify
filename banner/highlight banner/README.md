![placeholder](https://via.placeholder.com/1600x776.png?text=@taftera+Github+Tutorial)

Highlight Banner with pre-installed SVG icons | Shopify Help by @taftera
------

Lately, I've seen a lot of Shopify Stores with *highlight banners* they usually have the 4 same blocks: Credit Card availability, Easy Communication, Visit our Shops and Spread the love. 

As well, I had the opportunity of working with a premium template by [Pixel Union](https://pixelunion.net/) which made everything easier. But I had to add my flavor to it.

For this particular development, I needed to have full control of all the **24 SVG icons** (visual guide at the bottom), so I added them through a snippet.

```{% include 'highlight-banner-svg' %}```

This **SECTION** has the basic 2 / 3 / 4 block display configuration from the **Debut Theme** changing their size display and breakpoint depending on the number of blocks used.

![placeholder](https://via.placeholder.com/1600x776.png?text=@taftera+Github+Tutorial)

You'll see this options in the **highlight-banner** configuration:

+ HIGHLIGHT BANNER CONFIG
  + Padding height
  + Items Color (Both text options)
  + Background Color
+ DIRECTION CONFIG
  + Whether you'll like to see the icon and the text side by side (Horizontal) or stacked (vertical)

Each **block** will contain the next configurations:

+ IMAGE / SVG CONFIG
  + Image Select
  + SVG Icon Select
    + SVG Color
+ INFORMATION CONFIG
  + Header input
  + Font Size (21px)
  + Font Style (normal / **bold** / *italic*)
  + Support Information input
  + Font Size (13px)

How to install
------

### Adding Highlight Banner
1. Click [highlight-banner](https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/section/highlight-banner.liquid) and copy all the text
2. Enter **Online Store** > **Actions** > **Edit Code**
3. Under **Section** > Click **Add a new section**
4. Name it "highlight-banner".

![placeholder](https://via.placeholder.com/1600x776.png?text=@taftera+Github+Tutorial)

5. Paste all the text

### Adding SVG options
1. Click [svg-options](https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/snippets/highlight-banner-svg.liquid) and copy all the text
2. Enter **Online Store** > **Actions** > **Edit Code**
3. Under **Snippets** > Click **Add a new snippet**
4. Name it "**highlight-banner-svg.liquid**" (anything else will not work).
5. Paste all the text

Notes
------

## SVG Catalog (24)

<img src="https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/icon-reference/chat.svg" height="48"> | <img src="https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/icon-reference/chat-box.svg" height="48"> | <img src="https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/icon-reference/credit-card.svg" height="48"> | <img src="https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/icon-reference/delivery-truck.svg" height="48"> | <img src="https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/icon-reference/delivery-truck-fast.svg height="48"> | <img src="https://github.com/taftera/shopify-help/blob/master/banner/highlight%20banner/icon-reference/email.svg" height="48"> |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
Chat | Chat alt | Credit card | Delivery | Delivery alt | Email |
<img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> |
Email alt | Gift card | Location | Location alt | Lock closed | Lock open |
<img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> |
Lock digital | People | Price tag | Price tag: discount | Price tag: sale | Question |
<img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> | <img src="" height="48"> |
Shop | Shopping cart | Shopping cart alt | Smartphone | Smartphone fav | Smartphone shopping |

All icons were made by [xnimrodx](https://www.flaticon.com/authors/xnimrodx)

![placeholder](https://via.placeholder.com/1600x776.png?text=@taftera+Github+Tutorial)
# This is a heading