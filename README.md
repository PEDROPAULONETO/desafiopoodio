# Bootcamp DIO - Desafio POO Java
Este repositório contém a resolução do desafio de Orientação a Objetos (POO) em Java da Digital Innovation One (DIO), focado na simulação de um sistema de gerenciamento de bootcamps, cursos, mentorias e a progressão de desenvolvedores.
## Otimizações e Melhorias Implementadas
Neste commit, foram aplicadas otimizações para tornar o código mais conciso e legível, principalmente na forma como os conteúdos são adicionados ao Bootcamp.

### 🚀Otimização na Adição de Conteúdos
Anteriormente, cada Curso e Mentoria era adicionado individualmente à coleção de conteúdos do Bootcamp usando múltiplos bootcamp.getConteudos().add(...).

Agora, a adição de conteúdos foi otimizada utilizando List.of() em conjunto com addAll(), tornando o código mais limpo e direto:
```bash
JAVA

bootcamp.getConteudos().addAll(List.of(curso1, curso2, mentoria));
```
- #### Extração de Lógica de Impressão:
 Para evitar duplicação de código e melhorar a organização, a lógica de impressão do status do Dev (conteúdos inscritos, concluídos e XP) pode ser encapsulada em um método auxiliar. Isso tornaria o método main mais limpo e focado na orquestração da lógica de negócio.
- #### Melhoria de Mensagens:
 Padronizar e refinar as mensagens de saída do console para torná-las mais informativas e amigáveis.

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PEDROPAULONETO)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-paulo-da-silva-neto-8b8a20368/)
