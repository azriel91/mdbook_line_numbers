# Chapter 1

<details><summary>Rust code block:</summary>

````md
```rust
fn main() {
    println!("hello!");
}
```
````

</details>

```rust
fn main() {
    println!("hello!");
}
```

<details><summary>Rust code block with hidden lines.</summary>

````md
```rust
# use std::marker::PhantomData;
#
# fn main() {
println!("hello!");
# }
```
````

</details>

```rust
# use std::marker::PhantomData;
#
# fn main() {
println!("hello!");
# }
```

<details><summary>Python code block:</summary>

````md
```python
print("hello")
```
````

</details>

```python
print("hello")
```

<details><summary>Python code block with hidden lines:</summary>

```toml
# book.toml
[output.html.code.hidelines]
python = "~"
```

````md
```python
print("hello")
~ print("hidden")
print("world")
```
````

</details>

```python
print("hello")
~ print("hidden")
print("world")
```

<details><summary>Python code block with hidden lines (last line bug):</summary>

```toml
# book.toml
[output.html.code.hidelines]
python = "~"
```

````md
```python
print("hello")
~ print("world")
```
````

</details>

```python
print("hello")
~ print("world")
```
