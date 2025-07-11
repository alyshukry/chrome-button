
# ✨ Chrome Button Component

A chrome-style UI button with metallic gradients, designed by [@pxdx.studio](https://www.instagram.com/p/DHCNFL8Aciw/?igsh=MTdmd3VubXRtbnAzZg==) (and slightly edited) for use in your apps and projects.

## 💡 How to Use

1.  Download the CSS file or add it to your project.
    
2.  Copy the SVG gradient and include it in your HTML file.
    
3.  Add the class `chrome` to any element you want styled.
    
4.  Add the class `button` to make the button press in when hovered.
    
5.  To edit the width and height of your element, either:
    
    -   Change the variable values in the `.chrome` style.
        
    -   Or override them for your specific element, like so:
        

```css
.chrome.my-button { 
	--width: 5rem; 
	--height: 2.5rem;
} /* Sets the size for elements with the class '.my-button' */  
.my-button { 
	width: var(--width) !important;
	height: var(--height) !important;
}
```

----------

**License:** MIT  
**Contributing:** Contributions are welcome! Please feel free to submit a pull request.
