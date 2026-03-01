# typescript.md

**Syntax:**
- Use `type` instead of `interface`
- Use `function` instead of arrow functions
- Use `const Abc ... as const` instead of `enum Abc` with a second export for `const AbcType = typeof Abc[keyof typeof Abc]`

**Formatting:**
- Don't use semicolons
- Don't use trailing commas

**Types:**
- Always add types for function parameters and return types
- Only add types for function parameters and return types, unless required
