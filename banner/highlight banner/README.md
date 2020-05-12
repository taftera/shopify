![placeholder](https://via.placeholder.com/1600x776.png?text=@taftera+Github+Tutorial)

Highlight Banner with pre-installed SVG icons | Shopify Help by @taftera
------

Lately, I've seen a lot of Shopify Stores with *highlight banners* they usually have the 4 same blocks: Credit Card availability, Easy Communication, Visit our Shops and Spread the love. 

As well, I had the opportunity of working with a premium template by [Pixel Union](https://pixelunion.net/) which made everything easier. But I had to add my flavor to it.

For this particular development, I needed to have full control of all the [24 SVG icons](#svg-catalog-(24)) (made by [xnimrodx](https://www.flaticon.com/authors/xnimrodx)) so I added them through a snippet.

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

#SVG Catalog (24)

svg | svg | svg | svg | svg | svg |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
Chat | Chat alt | Credit card | Delivery | Delivery alt | Email |
svg | svg | svg | svg | svg | svg |
Email alt | Gift card | Location | Location alt | Lock closed | Lock open |
svg | svg | svg | svg | svg | svg |
Lock digital | People | Price tag | Price tag: discount | Price tag: sale | Question |
svg | svg | svg | svg | svg | svg |
Shop | Shopping cart | Shopping cart alt | Smartphone | Smartphone fav | Smartphone shopping |


![placeholder](https://via.placeholder.com/1600x776.png?text=@taftera+Github+Tutorial)
