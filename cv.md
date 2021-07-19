1.**Yury Ruzanau**, 27.

2.[E-mail](mailto:ruzanoff2009@yandex.by)

3.I think that working in programming and computer science is the highest degree
 of development and a **truly smart and beautiful job** at the present time. I'm
 fast learner and really like to do it.
 
4.Besides practice at the rs-school I was learning the 
[tutorial learn.javascript](https://learn.javascript.ru/) and completed  about 
60 percent of it. I had a practice on Codewars too.

5.Result on Codewars: 6 kyu, 144 points. [My codewars profile](https://www.codewars.com/users/PASSAGYR69)

6.**My code (JS):**

```
// "Primes in numbers" task from Codewars. Example: n = 86240 should return "(2**5)(5)(7**2)(11)"

function primeFactors(n) { 
  let arr = []
  let finalStr = ''

  prime:
  for (i = 2; i < Math.sqrt(n); i++ ) {
    for (j = 2; j < i; j++) {
      if (i % j == 0) continue prime;
    }
    while(true) {
      if (n % i == 0) {n = n / i; arr.push (i)}
      if (n % i != 0) {break}
    }
  }
  if(n > 1) arr.push(n);
  let step = 1;

  for (i = 0; i < arr.length; i++) {
    if (arr[i] == arr [i+1]) {
      step += 1
    }
    if (arr[i] != arr [i+1]) {
      step == 1 ?  finalStr += '(' + arr[i]  + ')' : finalStr += '(' + arr[i] +'**' + step + ')' ;
      step = 1;
    }
  }

  return (finalStr)
}
```

7.English-level A2.













