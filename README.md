# In my mind 🍀

```rust

struct Visionary {
    name: String,
    quote: String,
}

impl Visionary {
    /// Constructs a new `Visionary`.
    fn new(name: &str, quote: &str) -> Self {
        Self {
            name: name.to_owned(),
            quote: quote.to_owned(),
        }
    }

    /// Returns the quote of the visionary.
    fn quote(&self) -> &str {
        &self.quote
    }
}

fn main() {
    let gavin_wood = Visionary::new(
        "Gavin Wood",
        "In software, we’re not constrained by physical reality; \
         the only limits are the limits of our own imagination."
    );

    println!("{} says: \"{}\"", gavin_wood.name, gavin_wood.quote());
}
