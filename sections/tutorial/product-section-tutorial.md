![Project-03-PP-01](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_a.png)
# Adding a SECTION to a Product Page

In this tutorial, I'll be adding the newly developed [highlight banner](https://github.com/taftera/shopify-help) (*.liquid) to every Product Page

Tutorial 
------
1. First as always, you need to identify which **SECTION** and where is the code stored. 
   - Since we are just using the one in the highlight banner from previous  tutorial, it will be easier this time.
   - As well, at the bottom I'll add a link to a list of the basic ones on the **Debut** template.

2. Once you've got the section you are looking for, make a copy of the code and rename it: *name*-*destination*. In my case will be *highlight-banner*-product.liquid . This will allow us to display a a band with multiple options to assure our visitors simple information.
   - **Note:** due to the *settings_data.json* it's impossible to just link the section name to the final destination. Since it will take the variables from the front page edits and apply them to the page in question.
![Project-03-PP-02](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_b.png)

3. This example is a bit easier than the information page, open the *product.liquid* inside the Templates folder. And since we just need to add the code:

```
{% section 'highlight-banner-product' %}
```

- Where we want it:
   - Over 'product-template' (beneath the header)
   
   ![Project-03-PP-03](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_c.png)
   - Under 'product-template' (beneath the product and over the 'product-recommendation')
   
   ![Project-03-PP-04](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_d.png)
   - Or just above the footer (under the other 2 previous sections)
   
   ![Project-03-PP-05](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_e.png)

4. **Save**.

5. Go to the admin panel *(HOME)* and click on *Online Store* > Click the **Customize** button.

6. On the top you'll see the name of the template you are working on *Alex Debut - DEV* and right next to it **Home page** with a "▾". Click and scroll for the **Product pages**.
![Project-03-PP-06](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_f.png)

7. You'll need to set up the blocks for it to start displaying the information. [Highlight Banner Tutorial](https://github.com/taftera/shopify-help/tree/master/banner/highlight%20banner)
![Project-03-PP-07](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_g.png)

8. **TA-DAAA !** When loaded you'll see that there's the section you linked ! 
    - **Note:** Sadly product and information pages, can't arrange the sections position (just like I mentioned in **bullet 3**). So if you want to display the highlight banner in a different height, you need to go back to the *product.liquid*.
    
![Project-03-PP-08](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03-2_h.png)

[Basic Section Location](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/section-location.md)
------
In this link you'll find the basic sections and their file location within the Debut theme.

Thanks for reading my tutorial

Alex *:)*
