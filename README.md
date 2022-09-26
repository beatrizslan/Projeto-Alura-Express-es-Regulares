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

![Print Alura Midi](https://user-images.githubusercontent.com/105252003/186982896-20a40e9d-9a2e-4e3d-b707-d97844ac6a02.jpg)

### Links

- URL da solução: [JavaScript](https://github.com/beatrizslan/Projeto-Alura-Midi-JS/blob/main/docs/main.js)
- URL do site: [Site](https://beatrizslan.github.io/Projeto-Alura-Midi-JS/)

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

- Testador de regex - [Alura](https://beatrizslan.github.io/Projeto-Alura-Midi-JS/)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


### Agradecimentos

Gostaria de agradecer a toda equipe envolvida da Instituição Alura, pela excelente didática, plataforma de ensino e por disponibilizar projetos reais e profissionais que me ajudam muito a praticar e aprimorar todo meu conhecimento deste mundo incrível do Front-end.  

