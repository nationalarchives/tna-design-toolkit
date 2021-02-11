### Patterns
# Going back in a user journey
This pattern explains what to consider when the user wants to go back in a user journey e.g. filling out a form. The user can use various ways to achieve that, like clicking a back link on the page or the browser back button or typing the URL.

## Usage
Follow this pattern when you use


-Form e.g. question pages  https://design-system.service.gov.uk/patterns/question-pages/

-Back link https://design-system.service.gov.uk/components/back-link/

-Continue button

-Progress indicator (optional)

## Do's
-When going back to the previous page, it should be in the state the user last saw it. 

-Place the back link at the top of each page if it makes sense to do so. 

-Do not break the browser back button.

-Ensure the back link works even when JavaScript is not available. If that is not possible, then hide the back link.

-If the user has performed an action they should only do once, do not include a back link. Show a sensible message and do not let them perform the action again when they click the browser back button. 

![Sensible message](/images/sensible-message.png "sensible message")

## Research on this pattern
A back link should be included because some users do not trust browser back buttons when entering data. 