# Step 1 (Static vs Relative):
## What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.
### The sidebar changed its position on the document relative to its normal position.

# Step 2 (Fixed):
## Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?
### The footer stays in the same position when I scroll the page. The footer behave differently from position relative because it does not adjust to a specific value but stays at a fixed location.

# Step 3 (Absolute):
## What is the effect of position: absolute on an element? How is it different from fixed?
### The position absolute makes an elemeent relative to its nearest positioned ancestor. It is different from fixed position because fixed stays at a fixed position relative to its viewport unlike absolute.

# Step 4 : (Absolute):
## Why does the notice appear on top of the content? What happens if you swap the z‑index values?
### The notice appear on top of the content because it has a higher z-index value If you swap the z-index values, the content will appear on top of notice.

# Challenge:


## What changes that you have to do on the code that will position .notice box on the top right corner of the .content box? Please write the code on paper as well (both html and css on the part of .notice and .content).
### Set .content to position: relative and set .notice to position: absolute; top: 0; right: 0;
## Try to change the position of .content to relative then to fixed. What do you observed each time?
### Relative makes the position of contenet relative to its normal posiiton while fixed makes the position of the content fixed, even if you scroll the page.

## What do you observe on about the effect of z-index on .notice and .content boxes?
### The z-index makes the notice and content boxes appear on top of each other, when overlapped.


# Reflection:
## a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?
### Static is the default position, relative makes an element relative to its normal position, absolute makes an element relative to its nearest positioned ancestor and fixed makes and element fixed to its viewport.

## b. How does absolute positioning depend on its parent element?
### The absolute positioning depends on its parent element as a reference point.

## c. How do you differentiate sticky from fixed (you can research on sticky)?
### Sticky makes an element behave normally until it reaches a specific scroll point amount, unlike fixed which is permanently fixed to the viewport.

## d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples.
### If I were to design a webpage for a school event, I'll use positioning to highlight important information by making important details or dates fixed so that it is easier to identify. Other than that, I'll use relative positioning to organize other details.