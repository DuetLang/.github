## About
Derg (DergLang) is a programming language built to compile into native-capable Luau via a ***stupidly fast*** transpiler written in Zig and C.

It is currently mostly a solo project by [KnownSH](https://github.com/KnownSH) and the main compiler is not publically released yet.
```
MoneyLib.derg

--! Example taken and translated from Miners Haven's MoneyLib
export function LifeSkips(RB, Money) {
  const Cost = RebornPrice(RB)

  return :blk {
    for i = 20..1 {
      const Price = Cost * (10^(3*i))
      if Money > Price return :blk i
    }
  } else 0
}
```
