# show-soleti1
# Komala Soleti 
### CHICKEN TIKKA MASALA
##### I like <b>CHICKEN TIKKA MASALA</b> because, it is very tasty filled with lot of spices and herbs. It is one of the most authentic dish in North parts of <b>India</b>.
---
## Fav Food
### Three places where this above mentioned food is available 
1. Delhi
2. Mumbai
3. Hyderabad, it is very easy to get anywhere in these places.
### Three sides with which I would like to eat CHICKEN TIKKA MASALA are - 
 * nan
 * rice
 * salad
[My Movie link][https://github.com/Komala3/show-soleti1/blob/main/MyMovie.md]
---
# Fav Heros
4 fav characters that I like most are from ANIME, THOUGH they are played by non living actors , I wish them to be played by living legends, the characters are - Naruto, Itachi, Tsunade, Kakashi - 

# Table

| Hero Name      | Reason                                         | Age |
|----------------|------------------------------------------------|-----|
| Vijay          | Seems Hard working as character as Naruto     | 35  |
| Pawan Kalyan   | Same like Itachi very selfless                 | 53  |
| Vijay Shanthi  | Veteran actress with great action Skills as Tsunade | 58  |
| Mahesh Babu    | Same as Kakashi - witty and Handsome           | 49  |

# Favorite Quotes
---
> "The only thing we have to fear is fear itself": *- Franklin D. Roosevelt* 
---
> "That which does not kill us makes us stronger": *- Friedrich Nietzsche*
---
# Code Fencing

This code defines a debounce function, which is commonly used to limit the rate at which a function is called. Specifically, it makes sure that a function (fn) is only executed after a particular period of time (ms) has passed since the last time the debounced function was invoked. If the function is called again within that period, the previous call is cancelled, and the timer is reset.

```javascript
const debounce = (fn: Function, ms = 300) => {
	let timeoutId: ReturnType;
  return function (this: any, ...args: any[]) {
	  clearTimeout(timeoutId);
    timeoutId = setTimeout(() => fn.apply(this, args), ms);
  };
};
```

