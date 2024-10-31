## Hylcore

```rust

struct Visionary {
    name: String,
    quote: String,
}

fn main() {
    let gavin_wood = Visionary {
        name: "Gavin Wood".to_owned(),
        quote: "In software, we’re not constrained by physical reality; \
                the only limits are the limits of our own imagination.".to_owned(),
    };

    println!("{} says: \"{}\"", gavin_wood.name, gavin_wood.quote);
}
```





