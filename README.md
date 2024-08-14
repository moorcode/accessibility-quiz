# accessibility-quiz
Build a quiz webpage to learn accessibility tools such as keyboard shortcuts, ARIA attributes, and design best practices.

## Notes on Accessibilty

- A useful property of an SVG (scalable vector graphics) is that it contains a path attribute which allows the image to be scaled without affecting the resolution of the resultant image.

- To increase the page accessibility, the role attribute can be used to indicate the purpose behind an element on the page to assistive technologies. The role attribute is a part of the Web Accessibility Initiative (WAI), and accepts preset values.

- Typeface plays an important role in the accessibility of a page. Some fonts are easier to read than others, and this is especially true on low-resolution screens. Verdana and Tahoma (sans-serif) are web-safe.

- It is important to link each input to the corresponding label element. This provides assistive technology users with a visual reference to the input. This is done by giving the label a for attribute, which contains the id of the input.

- Using a placeholder is actually not a best-practice for accessibility; too often, users confuse the placeholder text with an actual input value - they think there is already a value in the input.

- Although not required for label elements with a nested input, it is still best-practice to explicitly link a label with its corresponding input element.

- Contrast between elements is a key factor. For example, the contrast between the text and the background of a heading should be at least 4.5:1.

- Certain types of motion-based animations can cause discomfort for some users. In particular, people with vestibular disorders have sensitivity to certain motion triggers.

- The navigation accessibility can be improved by providing keyboard shortcuts. The accesskey attribute accepts a space-separated list of access keys. Note: It is not always advised to use access keys, but they can be useful.

## Questions to ask yourself

1. Is this item descriptive enough?..Or should I add text only a screen reader can read (span with class="sr-only"), to avoid having to add visible text to the element?