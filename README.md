# thz-compiler — Compilador Self-Hosted THZ-LANG

Compilador da linguagem THZ-LANG escrito na própria sintaxe THZ (.thz).

## Estrutura
- driver.thz: Ponto de entrada do compilador
- lexer.thz: Tokenizador léxico
- parser.thz: Parser sintático e gerador de AST
- codegen.thz: Emissão de THZ-IR e LLVM IR

## Autonomia
Este módulo compõe a rota de auto-hospedagem (self-hosting) e autonomia nativa (Zero JVM).
