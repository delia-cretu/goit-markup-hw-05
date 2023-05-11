Homework #2

Criteria for work acceptance by the tutor
Project
«A1» All styles are contained in one styles.css file in the css folder.

«A2» Source code is formatted with Prettier.

«A3» All images and text content are taken from the layout.

«A4» All HTML pages have a style normalizer modern-normalize.

«A5» The code is in line with the guide.

«A6» The modal window script is linked in HTML as a separate file, modal.js.

Markup
«B1» HTML-markup is done for all layout elements.

«B2» Tags are used according to their semantics.

Styling
«C1» For all hover and focus effects (color, background, shadow), transitions are made. Time is set to 250ms, and the timing function is cubic-bezier(0.4, 0, 0.2, 1).

«C2» Transitions and animations explicitly specify the properties to be animated. There is no all value anywhere.

«C3» In the What We Do section, text with background is positioned over the image.

«C5» Blue overlay with text appears on the cards of the Portfolio page when hovering over any part of the card.
«C6» Blue overlay slides out from the bottom of the cards on the Portfolio page, as shown in the video.

Modal window

«D1» The markup and styling of the modal "backdrop" (dark semi-transparent background) are done.

«D2» "Backdrop" fills 100% of the height and width of the browser viewport and stays fixed in it.

«D3» The markup and styling of the modal window are done.

«D4» The modal window is vertically and horizontally positioned in the middle of the backdrop.

«D5» The markup and styling of the button for closing the modal window in the upper right corner are done.

«D6» By default, the modal and backdrop are hidden using the is-hidden class in the backdrop, whose selector uses the visibility, opacity and pointer-events properties.

«D7» If you remove the is-hidden class from the backdrop, the backdrop and modal window will appear.

«D8» The modal window opening/closing is animated using a transition with an arbitrary effect such as scale or translate, and opacity.

Modal window opening/closing
A modal window with the order form opens by clicking on the "Order a service" button. In order for the script to work, you need to add special attributes to the markup, used by the script to search for elements:

data-modal-open to the button for modal window opening;
data-modal-close to the button for modal window closing;
data-modal to the modal window's backdrop.
