# Meme Generator

In this project, I have completed the implementation of a **Meme Generator** app.

### Refer to the image below:

<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/meme-generator-output.gif" alt="meme-generator" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>

### Design Files

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/meme-generator-sm-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/meme-generator-lg-output-v0.png)

### Completion Instructions

The app has the following functionalities:

- Initially, values in the input elements are empty and the selected value in the select element is the first item in the given fontSizesOptionsList.
- When non-empty values are provided for **Image Url**, **Top Text**, **Bottom Text**, and **Font Size** and the **Generate** button is clicked:
  - The Image URL provided is applied as a background-image for the generated meme.
  - The given Top and Bottom text values appear at the top and bottom of the generated meme.
  - The selected font size value is applied to both the top and bottom text of the generated meme.

### Implementation Files

The following files were used to complete the implementation:

- `src/App.js`
- `src/components/MemeGenerator/index.js`
- `src/components/MemeGenerator/styledComponents.js`

### Important Note

**The following instructions are required for the tests to pass:**

- The HTML container element for the generated meme should have a `data-testid` attribute value as **meme**.
- When Styled Components are used, `data-testid` attribute should be used instead of `testid` attribute.

### Resources

**Image URLs**

- [https://assets.ccbp.in/frontend/react-js/nature-img.png](https://assets.ccbp.in/frontend/react-js/nature-img.png)

**Colors**

- ![#35469c](https://via.placeholder.com/150x50/35469c/000000?text=Hex:+35469c)
- ![#7e858e](https://via.placeholder.com/150x50/7e858e/000000?text=Hex:+7e858e)
- ![#5a7184](https://via.placeholder.com/150x50/5a7184/000000?text=Hex:+5a7184)
- ![#ffffff](https://via.placeholder.com/150x50/ffffff/000000?text=Hex:+ffffff)
- ![#d7dfe9](https://via.placeholder.com/150x50/d7dfe9/000000?text=Hex:+d7dfe9)
- ![#1e293b](https://via.placeholder.com/150x50/1e293b/000000?text=Hex:+1e293b)
- ![#0b69ff](https://via.placeholder.com/150x50/0b69ff/000000?text=Hex:+0b69ff)

**Font-families**

- Open Sans
