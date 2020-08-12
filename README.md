# Nitro JS - Lodash

Nitro uses a variety of JS libraries to make the magic happen. But there is no JS library more commonly `import`ed in Nitro than [`lodash`](https://lodash.com/).

Originally released in 2012, `lodash` is a light weight JS library made up of utility functions for common programming tasks. As you review its API, you may notice a lot of the functions look and operate similar to Ruby methods, such as `compact`, `sortBy`, and `values`.

Nitro imports functions from `lodash` in over 500 separate places (and counting). Listed below are commonly used `lodash` functions in Nitro, linked to `lodash`'s documentation.

Lodash docs are clear and concise. Each function has an **interactive** set of examples attached to it. For each of these commonly used functions, read the documentation and play with the examples.

- [map](https://lodash.com/docs/4.17.15#map)
- [get](https://lodash.com/docs/4.17.15#get) (like Ruby's `dig`)
- [merge](https://lodash.com/docs/4.17.15#merge)
- [pick](https://lodash.com/docs/4.17.15#pick)
- [omit](https://lodash.com/docs/4.17.15#omit)
- [compact](https://lodash.com/docs/4.17.15#compact)
- [noop](https://lodash.com/docs/4.17.15#noop)
- [take](https://lodash.com/docs/4.17.15#take)
- [filter](https://lodash.com/docs/4.17.15#filter) (like Ruby's `select`)
- [sortBy](https://lodash.com/docs/4.17.15#sortBy)
- [values](https://lodash.com/docs/4.17.15#values)
- [partial](https://lodash.com/docs/4.17.15#partial)
- [reduce](https://lodash.com/docs/4.17.15#reduce)
- [flow](https://lodash.com/docs/4.17.15#flow)
- [some](https://lodash.com/docs/4.17.15#some) (like Ruby's `any?`)
- [isEmpty](https://lodash.com/docs/4.17.15#isEmpty)
- [isEqual](https://lodash.com/docs/4.17.15#isEqual) (like Ruby's `==`)
- [isUndefined](https://lodash.com/docs/4.17.15#isUndefined)

## When to use `lodash`

A lot of `lodash` became obsolete with the release of ES6 in 2015. Since Nitro has been around since 2009, before Javascript included functions like `map` and `filter`, its codebase is filled with both `lodash`'s utility functions and their pure JS equivalents.

Q: Why would Nitro change to pure JS functions if it is was already using `lodash`?

A: Performance/speed

Check out the resources below to find benchmarks on how much faster pure JS is compared to `lodash`. Also check out the last resource link to view some side by side comparisons on how to use pure JS functions instead of `lodash`.

With all of that said, there are still some particularly useful `lodash` functions to reach for, such as `get` and `isEmpty`. Feel free to include `lodash` in your Final Project and use its functions that do not yet have JS equivalents.


### Resources

- [Why you shouldn't use lodash anymore and use pure Javascript instead](https://codeburst.io/why-you-shouldnt-use-lodash-anymore-and-use-pure-javascript-instead-c397df51a66)
- [Pure Javascript Functions as a Replacement for Lodash](https://blog.bitsrc.io/you-dont-need-lodash-or-how-i-started-loving-javascript-functions-3f45791fa6cd)
- [10 Lodash Features You Can Replace with ES6](https://www.sitepoint.com/lodash-features-replace-es6/)
