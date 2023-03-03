# Code Refactor Starter Code

The purpose of this project was to refactor Horiseon's existing site to make it more accessible & optimize for search engines. 


## Refactor Description

Application's CSS selectors and properties were consolidated and organized to follow semantic structure.

- Simplified `header` by replacing the an unnecessary `div` with a `nav` bar.

- Condensed the `div` container elements in class `content` to one class `card` in CSS.

- Condensed the `div` elements for the benefits section. Replaced individual classes with one parent class (benefits-lbc) for the 3 benefit options (lbc - lead generation, brande awareness, cost management).

Assigned 'id' attributes to each respective section in the .content `div`. All application links are now functional.

Added accessible alternative attributes to the icon & `img` elements.

Reordered the heading attributes so they fall in sequential order

Renamed the title element to a more concise, descriptive title. 

## Usage (Screenshot)

![Screenshot of updated Horiseon webpage](https://github.com/JordynEnos/code-refactor-horiseon/blob/main/Develop/assets/images/Horiseon-screenshot.png?raw=true)


## Differences from Original Code

Bug Fix: Search Engine optimization link was not functional & therefore inaccessible.

    The Application link has been corrected & is now functional.
