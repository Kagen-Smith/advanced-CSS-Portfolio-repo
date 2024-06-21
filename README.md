# advanced-CSS-Portfolio-repo

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

## Description 

[Visit the Deployed Site]()

This is my Portfolio, this will have examples of my work. this was a challenge by my teachers to teach me more about advanced CSS skills. I've met all of the criteria for what they wanted and I feel like i've done my best.


![Site Landing Page]()

https://kagen-smith.github.io/advanced-CSS-Portfolio-repo/

## Code Example
for coding this project it was very eye opening, in terms of seeing out CSS interacts with HTML. for example
```css
.flex-item {
  border: 5px solid var(--secondary);
  background-color: var(--primary);
  color:var(--tertiary);
  min-height: 150px;
  max-height: 150px;
  flex-basis: calc(50% - 1em);
  display: flex;
  align-items: flex-end;
  padding: 0 0 20px 0;
  margin: 0.5em;
  text-decoration: none;
  background-blend-mode: soft-light;
  background-size: 150%;
  transition: all 0.5s;
  font-size: 0.9rem;
}
```
this is a section of code for the box displaying my first project on the page. It was very tought to find out how to make the image show up inside of the box as it had a solid block of color. I tinkered around with this provided code and eventually added a background image element to it to add the image.

``` css
.flex-item {
  border: 5px solid var(--secondary);
  background-color: var(--primary);
  color:var(--tertiary);
  min-height: 150px;
  max-height: 150px;
  flex-basis: calc(50% - 1em);
  display: flex;
  align-items: flex-end;
  padding: 0 0 20px 0;
  margin: 0.5em;
  text-decoration: none;
  background-blend-mode: soft-light;
  background-size: 150%;
  transition: all 0.5s;
  font-size: 0.9rem;
  background-image: url("../images/Screen\ Shot\ 2024-06-16\ at\ 9.04.52\ AM.png");
}
```
like so.



## Learning Points 
I've learned a lot about advanced css from doing this project like:
1. what flexboxs are used for and how they can make sure the page displays correctly on different devices.
2. how a media element can change how the page is displayed at multiple sizes.
3. how to intergrate css within the HTML. 
4. how using a reset.css can help me achieve how I want a page to look like. 




## Author Info


### Kagen Smith


* [Portfolio](https://kagen-smith.github.io/advanced-CSS-Portfolio-repo/)
* [LinkedIn](https://www.linkedin.com/in/kagen-smith-4b22261a0/)
* [Github](https://github.com/Kagen-Smith)


## Credits




## License

MIT License

Copyright (c) [2024] [Kagen Smith]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.