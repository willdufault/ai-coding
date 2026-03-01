# typescript.md

**Syntax:**
- Use `type` instead of `interface`
- Use `function` instead of arrow functions
- Use `const Abc ... as const` instead of `enum Abc`, with a second export for `const AbcType = typeof Abc[keyof typeof Abc]`

**Formatting:**
- Omit semicolons
- Avoid trailing commas

**Type annotations:**
- Add types for function parameters and return values
- Add additional types only when necessary to satisfy static type checkers
