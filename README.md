# thz-compiler â€” Compilador Self-Hosted THZ-LANG

Compilador da linguagem THZ-LANG escrito na prÃ³pria sintaxe THZ (.thz).

## Estrutura
- driver.thz: Ponto de entrada do compilador
- lexer.thz: Tokenizador lÃ©xico
- parser.thz: Parser sintÃ¡tico e gerador de AST
- codegen.thz: EmissÃ£o de THZ-IR e LLVM IR

## Autonomia
Este mÃ³dulo compÃµe a rota de auto-hospedagem (self-hosting) e autonomia nativa (Zero JVM).
