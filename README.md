<div align="center">
  <h1>Falkara Digital Experience Template (Web)</h1>
</div>

<div align="center">
  <p>THE INTERNET MUST BE BUILT TOGETHER.</p>
  <p>GET INSPIRED BY OUR TECH STACK.</p>
</div>

<div align="center">
  <p>
    The FDET-W is a thoughtfully curated collection of technologies and tools that allows us to create a stellar digital experiences for the web environment. It balances aesthetics, usability, and resource costs, all with an overhead-free development experience.
  </p>
  <p>
    Get started by selecting this template when creating a new repository. Also available under the BSD-3-Clause license for cloning or forking; see the <a href="#license" alt="License section">License</a> section for more information.
  </p>
  <p>
    💫
  </p>
</div>

## Content

- [Expectations](#expectations)
- [Tech Stack](#tech-stack)
  - [JavaScript](#javascript)
  - [TypeScript](#typescript)
  - [Deno](#deno)
- [Support](#support)
- [README Template](#readme-template)
  - [Development](#development)
    - [Dependencies](#dependencies)
    - [Development Server](#development-server)
    - [Code Quality](#code-quality)
  - [Deployment](#deployment)
- [License](#license)

## Expectations

We're not just talking about the stellar experience – we're committed to delivering one. Below are the key challenges our tech stack is designed to tackle.

First, it must be based on a positive developer experience, as this directly influences a developer's attitude towards the project. We've identified three essential factors:

🔋 **Productivity Flow**

Creating new content or a pitch should be seamless, without requiring a complex mental map of all the necessary steps to achieve the desired feature.

🐲 **Creativity Surge**

The best ideas often emerge during the process, fueled by the possibilities and opportunities that the tools offer. No idea should be left unexplored because it "just didn't click".

🔩 **Delivery Confidence**

Nothing is more frustrating than introducing a new feature that inadvertently breaks an existing one, despite seeming unrelated. Or worse, discovering that locally tested creation behaves entirely differently in production. Merged code should be self-assured.

By having these key areas handled, the focus can be shifted to what matters most – crafting the digital experience that excels in the following areas:

🏛️ **Stable Foundation**

We want a solid foundation that doesn't panic or leave us feeling uncertain due to a chaotic ecosystem or unclear development direction.

💎 **Modern Appearance**

**Who was in Paris???** Got the attention? That's exactly how visuals and emotions capture the interest. In today's digital landscape, the visual aspect of a digital experience is paramount. It's about more than just a parallax effect – it's about creating a lasting impression.

🚄 **Astonishing Performance**

However, users are unforgiving. If something doesn't work, they're quick to lose interest. All the visual bells and whistles are meaningless if they take too long to load or glitch and stutter while running.

🧩 **Unchained Scalability**

After the creation handles first thousands of customers, we can finally ask the question that's been on everyone's mind: "Does it scale?" And the answer is, yes, it does.

The tech stack outlined below is designed to address all of these critical factors. By packaging it into a template, we get one more thing:

💆🏼‍♀️ **Streamlined Setup Process**

No need to repeat the same setup process over and over. Start coding immediately.

## Tech Stack

If you're familiar with our founder's blog post on development values and principles, you'll understand the underlying philosophy behind these choices. If not, we encourage you to read it for a deeper understanding. For those interested in raw reasoning only, feel free to skip ahead.

**Spoiler:** The blog post doesn't exist yet. Got trolled? 😤

This template is a work in progress, and new technologies that meet the criteria outlined above will be added gradually as they are being validated.

### JavaScript

| [WEBSITE](https://ecma-international.org/technical-committees/tc39/) | [DOCS](https://ecma-international.org/technical-committees/tc39/?tab=published-standards) |

[#FreeTheJavaScript](https://javascript.tm/)

We're part of the mankind that genuinely enjoys coding in JavaScript. Perhaps we've been subconsciously conditioned to accept its dominance in the frontend.

Using the same language on both the client and server simplifies development, increasing overall efficiency. And yes, we're willing to deal with the quirks, like [computing](https://github.com/denysdovhan/wtfjs?tab=readme-ov-file#precision-of-01--02) `0.1 + 0.2` as `0.30000000000000004`, on a daily basis.

What wasn't mentioned earlier is that this tech stack is also designed with sustainability in mind. _No greenwashing here._ We have knowledge around this tech stack and won't be reevaluating our choices weekly. We'd rather give a new kid on the block time to prove themselves, rather than blindly following their marketing claims about performance. We don't need performance; we use JavaScript.

But what about the "astonishing performance" mentioned earlier? Maybe we should rethink what "astonishing" means. The truth is, we don't need our visuals to be 55 μs faster when rewritten in Rust. 🦀

However, the massive community of JavaScript with such rapidly expanding ecosystem like this provides us with the possibility to do those rethinking processes on a weekly basis anyway, which is always a good backup thought.

### TypeScript

| [WEBSITE](https://typescriptlang.org/) | [DOCS](https://www.typescriptlang.org/docs/) | [REPOSITORY](https://github.com/microsoft/TypeScript/) |

We don't need to debate the imperfections of JavaScript. Let's talk... static typing!

Fortunately, our trusted linter comes to the rescue. Sadly, it's still under the influence of that one big corporation you thought is already done but somehow (linear algebra and cloud computing) became the most valuable company in the world anyway. 💸

We support deprecating TypeScript in favor of the [TC39 proposal for type annotations](https://github.com/tc39/proposal-type-annotations). On the other hand, TypeScript is MIT-licensed and does its job flawlessly.

### Deno

| [WEBSITE](https://deno.com/) | [DOCS](https://docs.deno.com/) | [REPOSITORY](https://github.com/denoland/deno) |

We don't need to debate the imperfections of JavaScript. Let's talk... standard library!

The capabilities of Deno's [standard library](https://docs.deno.com/runtime/fundamentals/standard_library/) exceed our expectations. But that's not all - Deno excels in many areas. Ryan Dahl really [knows what he is doing](https://www.youtube.com/watch?v=M3BM9TB-8yA). Where do we start?

- In the future, we might consider switching to a different language. If that happens, Deno is ready with native support for **WASM**.

- Deno also natively supports TypeScript, making it easy to use typed packages from **JSR**. Additionally, published packages include generated documentation.

- We agree with JSR's statement "ECMAScript modules have arrived as a standard." As JSR is **ESM**-only, it's our go-to choice for packages.

- Fewer dependencies are better. Deno's built-in **formatter** and **linter** replace Prettier and ESLint, simplifying the project structure.

- Deno also replaces pnpm and Vitest with its built-in **package manager** and **test runner**, making development even more efficient.

And yes, Deno is written in Rust. Did we just buy into the performance hype? 😩

## Support

<div align="center">
    <p>Did the template help you? Consider giving a tip.</p>
    <img src="./docs/BMC_Payment.webp" alt="Buy Me a Coffee payment QR code" width="200" /><br><br>
</div>

# README Template

**Repository README Checklist**

- [ ] Remove the whole content before this section
- [ ] Change the name of this section to the name of the repository
- [ ] Replace a placeholder below with a brief description of the digital experience
- [ ] Correct the link in the 'License' section
- [ ] Remove this checklist

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. t enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

## Content

- [Development](#development)
  - [Dependencies](#dependencies)
  - [Development Server](#development-server)
  - [Code Quality](#code-quality)
  - [Deployment](#deployment)
- [License](#license)

## Development

### Dependencies

To install the dependencies, run the following command:

```bash
deno install
```

### Development Server

To start the development server, run the following command:

```bash
deno task dev
```

### Code Quality

To format the code, run the following command:

```bash
deno fmt
```

To lint the code, run the following command:

```bash
deno lint
```

To run the unit tests, run the following command:

```bash
deno test
```

## License

This project is published under the BSD-3-Clause license. For more information, refer to the `LICENSE` file.
