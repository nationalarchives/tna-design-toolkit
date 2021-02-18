### Components
# Pagination
#### EXPERIMENTAL
This component is still in it's experimental stages and therefore only works with a small number of pages, there will be future iterations that can help with larger pages and will allow filtering, sorting and ordering. 

Use the Pagination component to help users browse through a long list.

![Pagination image](/images/pagination.png "pagination image")

## Usage
To use this component, you can use the below example. You must use the required [stylesheet](/components/pagination/styles.scss) in order for this component to work. 

#### HTML:
```html
    <nav role="navigation" aria-label="Pagination">
      <div class="pagination__summary">Showing 25 - 35 of 50 results</div>
      <ul class="pagination">
        <li class="pagination__item"><a class="pagination__link" href="#0" aria-label="Previous page"><span aria-hidden="true" role="presentation">&laquo;</span> Previous</a></li>
        <li class="pagination__item"><a class="pagination__link" href="#0" aria-current="true" aria-label="Page 1">1</a></li>
        <li class="pagination__item">...</li>
        <li class="pagination__item"><a class="pagination__link" href="#0" aria-label="Page 4">4</a></li>
        <li class="pagination__item"><a class="pagination__link current" href="#0" aria-label="Page 5, current page">5</a></li>
        <li class="pagination__item"><a class="pagination__link" href="#0" aria-label="Page 6">6</a></li>
        <li class="pagination__item">...</li>
        <li class="pagination__item"><a class="pagination__link " href="#0" aria-label="Page 10">10</a></li>
        <li class="pagination__item"><a class="pagination__link" href="#0" aria-label="Next page">Next <span aria-hidden="true" role="presentation">&raquo;</span></a></li>
      </ul>
    </nav>
```

## When to use this component
Pagination should only be used when a large amount of records are shown. If the record count is less than '50' then don't show pagination at all.

## How it works
The component can be configured to hide or show the result count, show which page is active, previous and next buttons, ellipses or numbers.

## Interaction principles
You can avoid pagination by:
- setting the default number of results per page (try 50 items on a page, although do test with users to get it right for that service)
- avoid infinite scrolling as this is problematic for keyboard-only users

## Content principles
Consider what the sorting order should be to make the search more relevant. The more specific it is to the user's search criteria, the better the search results.

## Accessibility
This component uses `aria-label` attribute which is used to define a string that labels the current element. This is useful in cases where a text label is not visible on the screen or if there isn't any indication of the purpose of the button.

There hasn't been any accessibility testing on this component yet.

## Research on this component
The design, code and guidance here are based on various other pagination components within government departments. Our component is using research from [HMCTS Design System](https://hmcts-design-system.herokuapp.com/components/pagination) and [Rural Payments](http://rural-payments-styleguide.herokuapp.com/pagination/).

TDR have also tested this pattern on their custom metadata page and most participants have given positive feedback by demonstrating that they were able to switch pages and identify that the page had been changed and the items within the list were updated.