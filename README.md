# Implicit Type Coercion in TypeScript

This example demonstrates how TypeScript's implicit type coercion can lead to runtime errors if not handled carefully. The `add` function is declared to accept two numbers, but the code passes a string, resulting in unexpected behavior at runtime.  The solution involves using type guards or stricter type checking to prevent such errors.