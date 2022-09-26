# Alura - Expressões Regulares

Estudo sobre Expressões Regulares durante o curso de Front-end da [Alura](https://www.alura.com.br/formacao-front-end).

## Indíce

**Visão Geral**
>[Desafio](#desafio) |
>[Screenshot](#screenshot) |
>[Links](#links)

**Meu Processo** 
>[O que eu aprendi](#o-que-eu-aprendi) | 
>[Recursos úteis](#recursos-úteis)

**Considerações Finais** 
>[Autor](#autor) |
>[Agradecimentos](#agradecimentos)

## Visão Geral

### Desafio

O desafio foi criar expressões regulares eficientes para validar formulários HTML e identificar CPF, CEP, emails e outros documentos.

### Screenshot

![Captura de Tela (218)](https://user-images.githubusercontent.com/105252003/192305389-b9466c6b-e8d4-4451-bdd1-485626c361e9.png)

### Links

- URL do testador de regex: [Testador de Regex](https://beatrizslan.github.io/Projeto-Alura-Expressoes-Regulares/)

## Meu processo

### O que eu aprendi

- O que são expressões regulares;
- Validação de formulários HTML;
- Identificar CPF, CEP, emails e outros documentos;
- Criação de expressões regulares eficientes;
- Uso classes, âncoras, quantifiers e grupos;
- Execução de expressões regulares na linguagem JavaScript.

```JS

function regexpTest() {
    var str = "Expressões regulares em JS";
    var regexp = new RegExp(/[j]/i);
    var n = regexp.test(str);
    alert(n);
}

regexpTest(); // retorna true

```

### Recursos úteis

- [Regex build](https://regex101.com/) - Esta é uma ferramenta sofisticada na web que você pode utilizar para escrever e analisar a sua regex.  

## Considerações Finais

### Autor

- Testador de regex - [Alura](https://beatrizslan.github.io/Projeto-Alura-Expressoes-Regulares/)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


### Agradecimentos

Gostaria de agradecer a toda equipe envolvida da Instituição Alura, pela excelente didática, plataforma de ensino e por disponibilizar projetos reais e profissionais que me ajudam muito a praticar e aprimorar todo meu conhecimento deste mundo incrível do Front-end.  
