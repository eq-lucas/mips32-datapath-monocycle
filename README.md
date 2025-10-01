# MIPSycle — Datapath MIPS Monociclo no Logisim Evolution

Um datapath MIPS monociclo feito no Logisim Evolution 3.9.0, com suporte a instruções dos formatos R, I e J.  
Projeto acadêmico que simula uma microarquitetura RISC baseada na ISA MIPS, implementada de forma modular e didática.

---

##  Sobre o projeto

Este trabalho implementa um processador monociclo baseado na arquitetura MIPS, com:

- Unidade Lógica e Aritmética (ULA) com operações: ADD, SUB, AND, OR, XOR, SLL, SRL, SLT  
- Banco de Registradores com leitura e escrita de 32 registradores de 32 bits  
- Decodificador de instruções e unidade de controle para gerenciamento dos sinais de controle  
- Memória de Instrução e Dados integradas ao datapath  
- Suporte a instruções MIPS dos formatos R, I e J, incluindo laços, estruturas condicionais e manipulação de memória  
- Projeto modular com subcircuitos independentes no Logisim Evolution 3.9.0

---

## Instruções suportadas

### Tipo R:
- ADD, SUB, AND, OR, SLL, SRL, SLT, XOR

### Tipo I:
- ADDI, ANDI, ORI, SLTI, LW, SW, BEQ, BNE

### Tipo J:
- JUMP

---
```plaintext
##  Estrutura do repositório


├── ULA.circ
├── BancoRegistradores.circ
├── Memoria.circ
├── MainDatapath.circ
├── exemplo.hex
├── README.md
├── Relatorio_MIPS_Monociclo.pdf (opcional)
``


---

## Autores

- Lucas Ferreira Dias — [ldias.2022@alunos.utfpr.edu.br](mailto:ldias.2022@alunos.utfpr.edu.br)  
- Luis Henrique Farias dos Santos — [luish10santos@gmail.com](mailto:luish10santos@gmail.com)  

Universidade Tecnológica Federal do Paraná – UTFPR  
Curso de Ciência da Computação – Campus Campo Mourão  

---

## Referências

- Arquitetura de Computadores MIPS, simulada no Logisim Evolution 3.9.0  
- Documentação e especificações MIPS ISA  

---

## Como usar

1. Abra os arquivos `.circ` no Logisim Evolution 3.9.0  
2. Simule o datapath monociclo e execute os programas em Assembly/Machine Code  
3. Explore cada subcircuito para entender a arquitetura modular  

---

## Contato

Para dúvidas, sugestões ou colaborações, entre em contato pelos emails dos autores acima.

---

Made in UTFPR  
