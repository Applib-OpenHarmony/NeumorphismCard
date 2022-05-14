# Neumorphism_Card
一Neumorphism Card design for OpenHarmony.

## Download & Install

Install using npm inside pages directory

```npm init -y```

```npm i hmos-neumorphism ```

Details about OpenHarmony NPM environment configuration, see at [here](https://gitee.com/openharmony-tpc/docs/blob/master/OpenHarmony_npm_usage.md)

## Usage Instructions
# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    color: black;
}
```

# Avatar

<img src="sample_images/avatar.png" width="" height="">

Import:
```html
<element name='neuavatar' src='hmos-neumorphism/avatar/avatar.hml'></element>
```

Usage:
```html
<neuavatar icon="common/icons/user.png" width="100px" height="100px" border="50px"></neuavatar>
```

# Card

<img src="sample_images/card.png" width="" height="">

Import:
```html
<element name='neucard' src='hmos-neumorphism/card/card.hml'></element>
```

Usage:
```html
<neucard width="300px" height="200px" border="10px" >
  <image src="common/placeholder.png" ></image>
</neucard>
```

## Compatibility
Supports OpenHarmony API version 6 

## Code Contribution
If you find any problems during usage, you can submit an [Issue](https://gitee.com/openharmony-sig/Card/issues) to us. Of course, we also welcome you to send us [PR](https://gitee.com/openharmony-sig/Card/pulls).

## Open source License
This project is based on [Apache License 2.0](https://gitee.com/openharmony-sig/Card/blob/master/LICENSE.txt) ，please enjoy and participate in open source freely.

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>
