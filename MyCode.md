# hello-world
My first steps in github.
I will add programs written by me while learning programming.


function fib(n) {

  //if (n<=1) return n; fajny zapis dwóch if poniżej
  if (n === 0)
    return 0;
  if (n === 1)
    return 1;

  var wynik = 0,
    a = 0,
    b = 1;
  for (var i = 2; i <= n; i++) {
    wynik = a + b;
    a = wynik;
    b = a;
  }
  return wynik;
}


console.log(fib(55));
