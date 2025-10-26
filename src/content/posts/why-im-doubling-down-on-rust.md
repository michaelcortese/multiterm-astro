---
title: "Why I'm doubling down on Rust (as a CS student)"
published: 2025-10-27
description: "An analytical (cough* amateur) perspective on the future of low-level programming in the age of AI"
draft: false
tags: ['Rust', 'Zed', 'AI']
---

### The world of bloat

Nowadays it feels like everyone is trying to sell you on something.

---

"You have GOT to try this new reasoning model"\
"NextJS just got a CRAZY update" (Yawn)

---

Frankly, I'm tired of it. All of this bloat makes me want to drown everything out and focus on one thing...

becoming the best developer I can be.

Now I'm going to sell you on something!

```rust
fn main() -> ! {
    println!("Hello, Rust!");
}
```

To become the best developer I can be, I'm choosing Rust. This is for a few key reasons:

1. Hope for the future
- If you're reading my blog, I assume we're in agreement that the AI hype is a little much. If we aren't in agreement, you are welcome to send me an angry email to which I will likely respond to. I believe the AI bubble is deflating, whilst the Rust (concrete) bubble can't deflate because it is made of concrete. Regardless, it is an undeniable fact that Rust is growing at an alarming rate, with more companies adopting it every year. In no way will it 100% replace it's predecessors like C or C++, but I am confident that it very easily could.
2. A passionate community
- As someone who has spent a LARGE chunk of their life *chronically* online, I can say firsthand that the community of Rust is unlike any other. There are literally thousands of developers in discord servers and subreddits that spend their time trying to inspire and support new Rustaceans. Sounds great, right? I haven't even mentioned the surplus of educational materials. Between the [Rust Book](https://doc.rust-lang.org/book/title-page.html), the [Rustonomicon](https://doc.rust-lang.org/nomicon/), and the countless others that exist for OS-dev, embedded, and foreign-function-interfaces, it has never been easier to begin your low-level development journey.
3. Open source!
- The Rust Foundation is a GIANT proponent of open source, and this philosophy has spread throughout the Rust community, with new projects popping up every day, and a never-ending supply of eager maintainers. As someone who has always been afraid of making contributions, Rust (and its community) have helped me make my first PR to [macroquad](https://github.com/not-fl3/macroquad), a lightweight game engine. Yes, the PR was tiny, BUT IT WAS A PR NONETHELESS! In addition to this, there are a countless number of fantastic, performant projects open-sourced in Rust. I don't have the time to list every single one, so I encourage you to check them out!

---

### Doubling down

So why, as a student, choosing to master a language before theory?

I believe that the language will help me understand the theory. Don't be misconstrued, however, I am NOT skipping the theory. By using the plethora of tooling written in Rust, I not only am able to comprehend the theory, but also the memory-based decisions behind it. When my peers are confronting a problem, I'm confronting the same problem, but then I can use my prior knowledge to *build on* that problem, and understand how the solutions can be morphed with the power of concurrency, and how the solutions can be implemented safer with the borrow checker philosophy.

---

### Does this matter to you?

Probably not. I'm skipping over the flaws like *slow compile times, complexity, and its verbose syntax*, but I'm trying to convince you to agree with me, not disagree (duh). Anyways of course this is all mostly just my opinions so I figured I'd share my thoughts for my first blog post.

-Michael out.
