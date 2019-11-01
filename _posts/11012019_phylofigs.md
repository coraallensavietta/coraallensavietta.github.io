---
layout: post
author: coraallencoleman
---

use this tutorial: 
https://jekyllrb.com/docs/step-by-step/08-blogging/

If we want to return n fibonacci numbers, we can do this with a for loop, while statement, or recursively. 

Which is fastest?

Here's a for loop function in Julia:
```julia
function fib_for(n)
    fib1 = 0
    fib2 = 1
    for i in 0:n-1
        sum = fib2
        fib1 = fib2
        fib2 = sum
        return fib1
    end
end
```

The fibonacci sequence with a while loop can be written in Julia as:
```julia
function fib_while(n)

    fib1 = 0, fib2 = 1;
    while (i < n)
    end
end
```

```julia
function fib_rec(n)
    if fib < 2
        return fib
    else
        fib_rec(fib - 1) + fib_rec(fib - 2)
    end
end

```