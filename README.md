# Resumo HTML

## HTML

O elemento raiz do nosso código fica dentro da tag `<html>`. Todo arquivo html deve iniciar com a estrutura abaixo:

### Exemplo:
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Texto da aba do site</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
</body>
</html>
```

### Principais características:
- O elemento `<html>` envolve todo o código da página
- O atributo `lang="pt-BR"` define o idioma da página para os navegadores

## Metadados

Metadados são informações sobre o documento que não aparecem diretamente na página, mas são usadas internamente pelos navegadores e ferramentas de busca. Eles são definidos dentro da tag <head>

### Exemplo de metadados:
```html
<head>
    <meta charset="UTF-8"> <!-- Define qual a codificação de caracteres, usamos esse pq nossa idioma possui acentos e etc -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Esse define a responsividade, para que o site funcione tanto no pc quanto no celular -->
    <meta name="description" content="Site sobre tecnologia e programação"> <!-- Descrição do site -->
    <meta name="author" content="Seu nome"> <!-- Autor do site -->
    <title>Meu Site</title> <!-- Esse define o nome que vai aparacer na aba no navegador -->
</head>
```






