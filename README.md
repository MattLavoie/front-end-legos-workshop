# Front End Legos Workshop

* [Presentation Slides](https://speakerdeck.com/shayhowe/front-end-legos-workshop-reusable-html-and-css)
* [Workshop Files](https://github.com/shayhowe/front-end-legos-workshop/archive/master.zip)

All too often writing HTML and CSS is an afterthought. Its the work that happens after design is finalized and the product has been developed. Its a necessary task in the process to building a website. Wrong.

HTML and CSS are the backbone to every website, and are equally as important as any design or development. At the end of the workshop and after spending time writing some of code attendees will be able to better organize their code, develop modular styles, and work with CSS specificity.

## #1 - Media Object

**Step 1:**

* Place a feed in to primary and secondary columns
* Float images to the left and content to right
* Visually offset the primary feed
* Visually offset one unique item inside the secondary column
* Reduce the width of the images within the secondary column

**Step 2:**

* Add borders around each primary item
* Add counts to a few primary items

**Step 3:**

* Reverse the position of images and content within the primary column, placing the images on the right and content on the left
* Leave any nested items within the primary column inversed, with images on the left and content on the right
* Reverse the position of images and content within any offset items in the secondary column, placing the images on the left and content on the right
* Change the "Posted&hellip;" text next to each name to be more subtle

## #2 - Buttons

**Step 1:**

* Add `View more`, `Start a new discussion`, and `Remove` buttons
  * Do not forget to account for different styles, sizes, and element types as outlined in the following steps

**Step 2:**

* Compose 5 different button styles, including:
 * `Default`, `Success`, `Warning`, `Danger`, `Boring`

**Step 3:**

* Compose 4 different buttons sizes, including:
  * `Default`, `Large`, `Small`, `Mini`

**Step 4:**

* Ensure the button styles that can be applied to any element, specifically including:
  * `a`, `button`, `input`, `span`, `div`

## #3 - Navigation

**Step 1:**

* Create a horizontal tab style navigation using an unordered list across the top of the primary column
  * Include links for `Discussions`, `To-dos`, and `Files`

**Step 2:**

* Create a horizontal pill style navigation using an unordered list across the top of the secondary column
  * Include links for `Today`, `Yesterday`, and `This Week`

**Step 3:**

* Using a media query, when a browser width falls below 640 pixels transform the horizontal list tab and pill style navigations into vertical list
  * Don't forget to take the mobile first approach into consideration

## Final Product

![Workshop Screenshot](screenshot.png)
