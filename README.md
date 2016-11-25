# simplic-lexer
Contains a simplie lexer / tokenizer for splitting strings into tokens with a custom ruleset.

1. Inherit from `ILexerConstants` and implement all required rules.
2. Use the tokenizer:

```csharp
var tokenizer = new Tokenizer(nwe LexerImplementation()); // <- Your custom implementation
tokenizer.Parse("Your Code Goes Here");
```
