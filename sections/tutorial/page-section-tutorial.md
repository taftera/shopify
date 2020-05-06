# Adding a SECTION to an Information Page

Tutorial 
------
1. First as always, you need to identify which **SECTION** and where is the code stored. At the bottom I'll create a list of the basic ones on the **Debut** template.
2. Once you've got the section you are looking for, make a copy of the code and rename it: *name*-*destination*. In my case will be *banner*-page.filetype. Since I've wanted to display a full width / adaptable image in my about page.
*Note:* due to the -file name- it's impossible to just link the section name to the final destination.
3. Since we are working with a normal information page, we need to create a specific type of page for it to work. Go to _name_ add page .
4. When created it will auto-load some basic page code with it's header {{ }} and information {{ }}. Depending on where you want it to be displayed you allocate the following code:
```
{% include 'banner.page' %}
```
5. SAVE !!! always save, doesn't matter if you change a character or you are about to face a DarkSouls Boss. Just SAVE.}
6. Create the page you want, and name it.
7. On the right side, there's a column named "Display", right before ending you'll see a drop-down, named "something" and a "page" named. Click on it and select the page you just created. In my case: **banner.page**
7. On to the **Customize** ( Shopify > area > Customize button )
8. On the top you'll see "where you are" with a drop-down menu. Click and search for the page you created. In my case: About-Us.
9. When loaded you'll see that there's the section you linked !

*Extra note:* If you want to add multiple diferent pages with the same **SECTION**, sadly you'll need to create another copy of the SECTION and repeat the process. Well, until I find a better way.

Thanks for reading my tutorial :)
