![Project_03-F](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_f.jpg)
# Adding a SECTION to an Information Page

In this tutorial, I'll be adding the banner or (hero.liquid) to an information page.

Tutorial 
------
1. First as always, you need to identify which **SECTION** and where is the code stored. 
   - At the bottom I'll link to a list of the basic ones on the **Debut** template.
2. Once you've got the section you are looking for, make a copy of the code and rename it: *name*-*destination*. In my case will be *hero*-page.liquid. Since I've wanted to display a full width / adaptable image in my about page.
   - **Note:** due to the *settings_data.json* it's impossible to just link the section name to the final destination. Since it will take the variables from the front page edits and apply them to the page in question.
![Project_03-A](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_a.jpg)
3. As we are working with a normal information page, we need to create a specific type of page for it to work. 
   - Go to **Templates**
   - Add a new template
   - Select **page** from the drop-down menu
   - Name your page. As we are creating an information page with a *hero.liquid* I'll name it **hero_one**.
![Project_03-B](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_b.jpg)
4. When created, after a few seconds, it will auto-load some basic page code with it's title **{{ page.title }}** and information **{{ page.content }}**. Depending on where you want it to be displayed you allocate the following code:
```
{% section 'hero-page' %}
```
![Project_03-C](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_c.jpg)
5. **SAVE !!!** always save, doesn't matter if you change a character or you are about to face a DarkSouls Boss. Just **SAVE**.
6. Go back the the admin panel *(HOME)* and click on *Online Store* > *Pages*
7. Add the page you want, and name it. Since I'm making an "About Us" page I'll name it just like it.
![Project_03-D](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_d.jpg)
9. On the right side, there's a column with a block named "Visibility", the next block is named "Template" at the end of it, you'll see a drop-down, named "template-sufix" and a "page" selected. Click on it and select the page you just created. In my case: **page.hero_one**
9. On to the **Customization**. Go back the the admin panel *(HOME)* and click on *Online Store* > Click the *Customize* button.
10. On the top you'll see the name of the template you are working on *Alex Debut - DEV* and right next to it **Home page** with a "▼". Click and scroll for the page you created. In my case: About Us, under **PAGES**.
![Project_03-E](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_e.jpg)
11. **TA-DAAA !** When loaded you'll see that there's the section you linked !
![Project_03-F](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_f.jpg)
![Project_03-G](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/screenshots/gh-display_03_g.jpg)

**Extra note:** If you want to add multiple diferent pages with the same **SECTION**, sadly you'll need to create another copy of the SECTION and repeat the process. Well, until I find a better way.

[Section Location](https://github.com/taftera/shopify-help/blob/master/sections/tutorial/section-location.md)
------
In this link you'll find the basic sections and their file location within the Debut theme.

Thanks for reading my tutorial :)