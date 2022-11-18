## lox_j

My step-by-step implementation of the Lox language from the book [Crafting Interpreters](https://www.craftinginterpreters.com).

### How to run

Build the project:

```bash
./gradlew build
```

If you want to generate `Expr.java`, try this:

```bash
java -cp ./app/build/classes/java/main/ tool.GenerateAst
```

Or try our AST printer:

```bash
java -cp ./app/build/classes/java/main/ lox.AstPrinter
```
