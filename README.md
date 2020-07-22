
## 🙌  Freelance Developer

### 😍 &nbsp;Full-Stack Engineering
### 🐳 &nbsp;Blockchain Development
### `λ` Functional Programming

##

```erlang
function
  to_str : int * list(int * string) => string
  to_str((_, [(_, s1)]))          = s1
  to_str((_, [(_, s1), (_, s2)])) = String.concat(s1, s2)
  to_str((x, _))                  = Int.to_str(x)
    
entrypoint fizz_buzz(to : int) : list(string) = 
  let fizz_or_buzz = (x) => [ (m, s) | (m, s) <- [(3, "Fizz"), (5, "Buzz")], if(x mod m == 0) ]
  [ to_str((x, fizz_or_buzz(x))) | x <- [1..to] ]
  ```
