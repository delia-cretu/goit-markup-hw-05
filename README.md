Homework #2

«C2» Transitions and animations explicitly specify the properties to be animated. There is no all value anywhere.

Modal window

«D6» By default, the modal and backdrop are hidden using the is-hidden class in the backdrop, whose selector uses the visibility, opacity and pointer-events properties.
«D8» The modal window opening/closing is animated using a transition with an arbitrary effect such as scale or translate, and opacity.

Modal window opening/closing
A modal window with the order form opens by clicking on the "Order a service" button. In order for the script to work, you need to add special attributes to the markup, used by the script to search for elements:

data-modal-open to the button for modal window opening;
data-modal-close to the button for modal window closing;
data-modal to the modal window's backdrop.
