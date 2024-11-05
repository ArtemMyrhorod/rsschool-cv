# Artem Myrhorod
## Contact me:
* [Telegram](@ArtemMyrhorod "Telegram")
* [Gmail](mirgorodartem@gmail.com "Gmail")

My main goal is to become a good worker.

## My set of skills:
* HTML 
* CSS
* JavaScript
* React
* Git

Here are some examples of my code from CodeWars:
* Find out whether the shape is a cube
```
var cubeChecker = function (volume, side) {
  if (side <= 0) {
    return false;
  } else if (volume != side*side*side) {
    return false
  } else {
    return true;
  }
};
```
* A Chain adding function
```
var add = function(n) {
  const f = x => add(n + x)
  f.valueOf = () => n
  return f;
}
```
* A String of Sorts
```
function sortString(string,ordering) {
  ordering=ordering.split``
  let arr1 = string.split``.filter(v=>ordering.includes(v)).sort((a,b)=>ordering.indexOf(a)-ordering.indexOf(b))
  let arr2 = string.split``.filter(v=>!ordering.includes(v))
  return arr1.join``+arr2.join``
}
```
* A Rule of Divisibility by 13
```
function third(n) {
   const dict=[1, 10, 9, 12, 3, 4]
   let sum=n;
   while(1){
       let temp=sum
       sum=sum.toString().split``.reverse().join``.split``.map((v,i)=>{
         v=v*dict[i%6]
         return v
       }).reduce((a,b)=>a+b,0)
       if (sum===temp){break}
     }
   return sum
}
```

Here you can check my projects on Upwork platform:
[Upwork](https://www.upwork.com/freelancers/~015d34cb509d1ea415 "Upwork")

My list of languages are following:
* Ukrainian
* Russian
* English
* Swedish