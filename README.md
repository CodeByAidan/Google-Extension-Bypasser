# Google-Extension-Bypasser
A neat and simple way that utilizes chrome's webstore to reverse-engineer and bypass a user's organization account/profile block on disabling/enabling chrome extensions.

Source is active using GitHub's Pages:
[site](https://CodeByAidan.github.io/Google-Extension-Bypasser/site.js)

```javascript
javascript:fetch(`https://CodeByAidan.github.io/Google-Extension-Bypasser/site.js`).then(data=>{data.text().then(text=>{eval(text)})});
```
*or*
```javascript
javascript : fetch(`https://CodeByAidan.github.io/Google-Extension-Bypasser/site.js`).then(data =>  {
data.text().then(text =>  {
eval(text)}
)}
);
```
