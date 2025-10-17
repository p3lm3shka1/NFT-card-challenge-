# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Screenshot

<img width="400" height="700" alt="image" src="https://github.com/user-attachments/assets/eba90c0b-ef26-42d5-9382-c82816441d2d" />

### Links

Live site URL : https://p3lm3shka1.github.io/NFT-card-challenge-/
Repository URL : https://github.com/p3lm3shka1/NFT-card-challenge-

## My process

- Semantic **HTML5** markup  
- **CSS custom properties**  
- **Flexbox** for layout alignment  
- **Responsive design** with media queries  
- **Hover effects** using CSS transitions  

### What I learned

While building this project, I learned how to:

- Create a **hover overlay** using absolute positioning and opacity transitions  
- Use **CSS transitions** for smooth hover animations  
- Style and align icons and text within a flex container  
- Build **responsive layouts** that adjust for smaller screens

Example hover overlay effect:

```css
.layer {
  position: absolute;
  border-radius: 10px;
  background: hsl(178, 100%, 50%);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.layer:hover {
  opacity: 0.5;
  cursor: pointer;
}
```

Example responsive styling:

```css
@media (max-width: 480px) {
  .card {
    width: 90%;
    height: auto;
    margin-top: 50px;
  }
}
```
