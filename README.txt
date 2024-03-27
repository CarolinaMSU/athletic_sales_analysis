For this assignment I followed a similar process to what I have done before;
- I looked at assignments that had similar code/activities and copied and pasted the code.
- Updated names of df's and variables as needed

Since I've been having issues with syntax, I used chat GPT to correct my code when I made mistakes, for example, I'd say:
-   me: what is syntax error in this code: women_footwear = athletic_sales_20_21_df[athletic_sales_20_21_df['product].str.contains("Women\'s Athletic Footwear")]
    ChatGPT
    The syntax error in the code you provided seems to be a missing closing square bracket (]) after the string 'product'. The closing square bracket should come after 'product', like this:
    athletic_sales_20_21_df['product'].str.contains("Women\'s Athletic Footwear")]
    Ensure that you have the correct column name ('product') and the pattern you're searching for within the str.contains() method is properly formatted.
This was helpful to me because it helped me see that I was missing a " ' " in this section: ['product]
I like the option of using ChatGPT for these types of corrections as opposed to the online assistant, I rather use their time to understand concepts or functions instead of what is basically "spell check" in syntax errors.

This assignment had repetitive requests; i.e. renaming, creating pivot tables, etc. so Once I got the right commands I was able to copy/paste as needed and update my variables.

The main section I had an issue with was the change of the valiable that had "Women's Athletic Footwear" because the variable already has an ' as part of the name and that is what I had been using all along in my code, so I rewatched the recording from monday and I saw that one of my teammates had the same issue, and they fixed it by adding a "\".
There was no way I would've figured that out on my own as I was unsure how to even ask that question since it was part of the variable. 

I get the concepts, right now I am just trying to memorize when we use the [, {, (, ' or ". It is kind of like learning how to spell.