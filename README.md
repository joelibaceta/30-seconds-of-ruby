# 30 seconds of code

> Note: This project is inspired by 30 Seconds of Code, but there is no affiliation with that project.

### 📚 Array

<details>
<summary>View contents</summary>

* [`any?`](#any?)


---
 ## 📚 Array

### any?
Passes each element of the collection to the given block. The method returns `true` if the block ever returns a value other than `false` or `nil`.

```ruby
%w[ant bear cat].any? { |word| word.length >= 3 } #=> true
%w[ant bear cat].any? { |word| word.length >= 4 } #=> true
[nil, true, 99].any?                              #=> true
```
