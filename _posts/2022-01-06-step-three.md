---
layout: default
title:  "Step Three"
date:   2022-01-06 12:00:00 -0400
categories: jekyll update
---
## Add Materials and Textures

TBD

## Code Snippets

### Sky

```javascript
    /**** Sky Color *****/
    scene.clearColor = BABYLON.Color3.Black();
```

### Ground Material & Texture

```javascript
    var groundMat = new BABYLON.StandardMaterial("groundMaterial");
    groundMat.diffuseTexture = new BABYLON.Texture("https://raw.githubusercontent.com/aprilspeight/workshop-babylonjs/main/rm187-mynt-34.jpg", scene);   
    groundMat.diffuseTexture.uScale = 4;
    groundMat.diffuseTexture.vScale = 4;
    groundMat.specularColor = new BABYLON.Color3(.1, .1, .1);
    ground.material = groundMat;
```

## Complete Code

```javascript

```

<ul class="actions">
<li><a href="https://aprilspeight.github.io/workshop-babylonjs/jekyll/update/2022/01/07/step-two.html" class="button special">Back</a></li>
<li><a href="https://aprilspeight.github.io/workshop-babylonjs/jekyll/update/2022/01/05/step-four.html" class="button">Next</a></li>
</ul>