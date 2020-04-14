Banner with mobile specific image | Shopify Help
------

Usually when I develop, many of the banners we use aren't the same when people use their phones. I don't know why it hasn't been pre-installed but this is a life saver.

Also, I've added a few other configurations, instead of just being able to see text centered, you can displayed it *left* and *right* alignment.
For this particular development, this section buttons need an arrow "→", therefore I added a SVG file in the snippets by including it.

```{% include 'btn_arrow' %}```

I used **hero.liquid** as base (2020-03)

You'll see a few extra options:

+ checkbox > "Enable Mobile Banner"
+ image picker > "Mobile Image"
+ checkbox > "Add →"
+ select > "Text Alignment"
+ range > "Margin Bottom"

How to install
------

### Adding Banner
1. Click [banner](https://github.com/taftera/shopify/blob/master/banner/banner%20w%20mobile%20img/section/banner.liquid) and copy all the text
2. Enter **Online Store** > **Actions** > **Edit Code**
3. Under **Section** > Click **Add a new section**
4. Rename it how you want it.
5. Paste all the text

### Adding SVG Arrow "→" to button
1. Click [btn_arrow](https://github.com/taftera/shopify/blob/master/banner/banner%20w%20mobile%20img/snippets/btn_arrow.svg.liquid) and copy all the text
2. Enter **Online Store** > **Actions** > **Edit Code**
3. Under **Snippets** > Click **Add a new snippet**
4. Name it "**btn_arrow.svg**" (anything else will not work).
5. Paste all the text

Notes
------
If by any chance you cant see the mobile image displayed, double check the "Enable Mobile Banner" it has been a few times I've re-check my code for this simple thing.

Project - [adidas Watches Mexico](https://adidas-watches-mexico.myshopify.com/)
