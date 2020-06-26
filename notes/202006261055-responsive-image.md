## 202006261055 Responsive images

#css #images #code

To have a responsive image which works everywhere you put it in a relative parent. You keeep the image ratio with a percentage on the padding property. 
The image is a full size absolute child.

```css
.wrapper {
  position: relative;
  padding-top: 56.25%; /* 16:9 Aspect Ratio */
}
img {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: auto;
}
```

=> The Netflix way

Linked to: [Fluidity in design](https://github.com/AJuliette/zettelkasten/blob/master/notes/202006071040-fluidity-in-design.md)
Source: [Time-saving CSS techniques to create responsive images](https://medium.com/free-code-camp/time-saving-css-techniques-to-create-responsive-images-ebb1e84f90d5)
