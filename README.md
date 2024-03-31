# Portfolio


## Prototyping

The creation started when our professor from the UX Design class tasked us to do the low fidelity wireframe. The reason for this minimal design is that I have contents that will likely compete my website design that is why I opted not to give too much elements.

Attached below is the image for my low fidelity prototype
![Low fidelity prototype](./images/md_Images/Screenshot%202024-03-31%20143850.png)

Come to a time that we're done with the high fidelity layout, we had the chance to show it to our classmates and get their feedback what to remove or retain. I honestly had a feeling that the cards below the banner is overwhelming or too much elements, someone had suggested that I remove the buttons as clicking the image can already lead the users to the projects' link. So I decided to remove it, and improve the header as the nav links were smaller on the low-fidelity prototype.

Here's the final look before I do coding.
![High-Fidelity Prototype](./images/md_Images/Screenshot%202024-03-31%20145003.png) 

## And now the coding part...

As I have said earlier, the design is not too much complicated but I have too much pages because most of it were dedicated for categories, and also write-up explanations for individual projects specifically for graphic design and web development. I have to code first the page for each project since it has the simplest design but other than that, it has to be repeated at least nine times. 

### File linking
This is my first problematic encounter when I am on my early stage of coding my projects page. I have already finished the layout and pushed the code to my GitHub repository. Local render was fine but when I tried to enter the github pages link, my layout and images didn't render although I believed that time that all assets were linked properly to my HTML files. 

I tried to read some internet discussions regarding github pages and found out that I missed a detail. When it comes to linking and my file is in a subdirectory, it is required to do e.g. '../css/styles.css' since it is a relative path and the browser will be able to find it and apply my styles to the page.

<!-- "Tell us about your process, challenges you faced during development and how you overcame those changes. What have you learned by creating your web portfolio?" -->



### Assets used

**Frameworks**
- [Bootstrap](https://getbootstrap.com/)
- [Animate on Scroll](https://michalsnik.github.io/aos/)
- Back to Top button - Courtesy of [MDBootstrap](https://mdbootstrap.com/snippets/standard/mdbootstrap/2964350)
- Image masonry layout courtesy of [Infinite Scroll](https://infinite-scroll.com/demo/masonry/)

**Fonts**
- Icons courtesy of [BoxIcons](https://boxicons.com/)
- Neutro font courtesy of [CDN Fonts](https://www.cdnfonts.com/neutro.font)
- Archivo font courtesy of [Google Fonts](https://fonts.google.com/specimen/Archivo?query=archivo)