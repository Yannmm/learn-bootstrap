`tailwind-css` and `bootstrap` are rivals that i think both of them I will use in future. So I will learn `tailwind-css` as well.


## Calculating a property's actual value
The user agent performs four steps to calculate a property's actual (final) value:

- First, the specified value is determined based on the result of cascading, inheritance, or using the initial value.
- Next, the computed value is calculated according to the specification (for example, a span with `position: absolute` will have its computed display changed to block).
- Then, layout is calculated, resulting in the used value.
- Finally, the used value is transformed according to the limitations of the local environment, resulting in the actual value.