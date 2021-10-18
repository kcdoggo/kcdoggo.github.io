---
layout: post
title:  "react slideshow image"
categories: React
---
React slideshow image
https://www.npmjs.com/package/react-slideshow-image
https://react-slideshow.herokuapp.com/

이미지는 public폴더에 images폴더를 생성하고, 거기 이미지를 넣는다. 
```javascript

  const slideImages = [
        'images/main.svg',
        'images/main2.svg'
      ];

 <div className="slide-container">
        <Slide>
         {slideImages.map((slideImage, index)=> (
            <div className="each-slide" key={index}>
              <div style={{'backgroundImage': `url(${slideImage})`}}>
              </div>
            </div>
          ))} 
        </Slide>

```