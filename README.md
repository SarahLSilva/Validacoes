<h1 align="center">Validação de CPF e Email</h1>

<p align="center">
  🚀  Este projeto valida CPFs e emails diretamente no navegador. Os usuários recebem feedback imediato após inserir os dados nos formulários correspondentes. Implementado com HTML, CSS e JavaScript.

---

## 📋 Sumário

- [Funcionalidades](#funcionalidades)
- [Validação do CPF](#Validação-do-CPF)
- [Validação do Email](#Validação-do-Email)
- [Tecnologias](#tecnologias)
- [Explanação de codigos](#Explanação-de-codigos)
- [Autor](#Autor)

---

## ✨ Funcionalidades

Validar o CPF e o cadastro do e-mail é muito importante para garantir a veracidade e confiabilidade dos dados. A verificação do CPF garante que o número fornecido está correto e corresponde ao cadastro original, evitando fraudes e erros. O e-mail garante que o formato do endereço esteja correto e pode evitar erros de comunicação. Essas validações melhoram a confiabilidade do cadastro e garantem a veracidade das informações e a boa interação com os usuários.


---

## Validação do CPF

![cpfErro](img/cpfErro.png)
![cpfCorreto](img/cpfCorreto.png)

### Método

  - O Projeto de Validação de CPF utiliza HTML, JavaScript e CSS para criar páginas totalmente funcionais e elegantes. O HTML define um formulário com campo de entrada de CPF e botão de envio. JavaScript verifica o CPF removendo caracteres não numéricos e calculando dígitos de verificação, e exibe uma mensagem de verificação apropriada. O CSS molda a página centralizando formulários, aplicando imagens de fundo e ajustando a aparência dos elementos para garantir uma experiência de usuário atraente e intuitiva. Juntos, esses componentes criam uma ferramenta eficaz para verificar a validade de um número de CPF.

### Explanação de codigos 
<br>
/HTML/ <br>
  - O <! DOCTYPE html> define o documento como HTML5. Dentro da estrutura HTML, o < head> inclui informações como o título da página e links para o estilo visual (CSS). O < body> contém um formulário para inserir e validar o CPF, com um campo de texto, um botão de submissão e um parágrafo para exibir mensagens de validação. O JavaScript, incluído no final, faz a validação do CPF inserido e atualiza a mensagem com base na validade do número.
<br>
/JAVASCRIPT/<br>
  - Quando o formulário é enviado, o padrão de recarregar a página é impedido. O código então pega o CPF digitado e usa uma função para checar se ele é válido. A mensagem na página é atualizada de acordo com o resultado da validação.
  A função de validação remove caracteres extras do CPF e verifica se ele tem 11 dígitos e se não é feito só de números repetidos. Em seguida, calcula dois números de verificação com base nos dígitos do CPF e compara com os números de verificação fornecidos. Se tudo estiver certo, a função retorna true; se não, retorna false.
/CSS/<br>
  - Estilo para o Corpo da Página: Define a fonte, imagem de fundo, e o layout usando Flexbox para centralizar o conteúdo vertical e horizontalmente.
  Define a altura da viewport para ocupar toda a altura da tela e remove a margem.
  Estiliza o Contêiner Principal (div):

  Define a cor de fundo, padding, borda arredondada, sombra e largura do contêiner.







## Validação do Email

![emailErro](img/emailErro.png)
![emailCorreto](img/emailCorreto.png)

### Método

  A página de verificação de e-mail usa HTML, JavaScript e CSS para criar uma interface funcional e estética. HTML Crie uma página usando um formulário contendo um campo de e-mail e um botão de envio. JavaScript valida o e-mail inserido: Se o e-mail estiver vazio ou não contiver os caracteres @ e . um aviso aparece informando que é necessário um e-mail válido. O conteúdo é centralizado, as cores aplicadas e as bordas arredondadas garantem uma boa experiência visual. Juntas, essas tecnologias garantem que as entradas de e-mail sejam devidamente validadas e exibidas de forma clara ao usuário.

### Explanação de codigos

/HTML/

  - Estrutura Básica: Define o tipo de documento e a estrutura HTML básica, com < head> para metadados e < body> para o conteúdo visível.
Meta Tags: Configuram a codificação de caracteres e a compatibilidade com diferentes navegadores.
Link para CSS: Conecta o arquivo de estilo externo cssemail.css que estiliza a página.
Formulário: Inclui um campo de entrada para e-mail e um botão de envio. O botão possui atributos onclick e onblur que chamam a função checarEmail para validar o e-mail inserido.
Parágrafo para Mensagem: Um elemento < p> com o ID email onde será exibido o resultado da validação do e-mail.
Inclusão do JavaScript: O arquivo email.js é incluído para fornecer a funcionalidade de validação.

/JAVASCRIPT/

  - Função checarEmail: Responsável pela validação do e-mail inserido pelo usuário.
Obtendo o Valor: A função obtém o valor do campo de e-mail usando document.forms[0].email.value.
Validação: Verifica se o e-mail está vazio ou não contém os caracteres essenciais (@ e .). Se não atender a essas condições, exibe um alerta informando o usuário sobre a necessidade de um e-mail válido e encerra a função.
Confirmação: Se o e-mail for considerado válido, exibe um alerta de sucesso.
Atualização da Página: O e-mail informado é exibido no parágrafo com o ID email.

/CSS/

  - stilo do Corpo (body):
Fonte e Layout: Define a fonte padrão e usa Flexbox para centralizar o formulário vertical e horizontalmente.
Imagem de Fundo: Aplica uma imagem de fundo e remove as margens padrão.
Estilo do Formulário (form):
Estilo Visual: Define o fundo branco, padding, bordas arredondadas e uma sombra leve para criar um visual moderno e destacado.
Estilo das Etiquetas (label):
Estilo do Texto: Exibe as etiquetas como blocos com margens inferiores e fonte em negrito para destaque.
Estilo do Campo de Entrada (input[ type="text"]):
Largura e Padding: Ajusta a largura, o padding e o estilo da borda para tornar o campo de entrada mais utilizável e esteticamente agradável.
Estilo do Botão (input[ type="submit"]):
Aparência do Botão: Define padding, tamanho da fonte, cor de fundo, e estilo de borda para o botão, além de um cursor pointer para indicar que é clicável.
Estilo da Mensagem (#email):
Estilo do Texto: Define a cor e o estilo da fonte para a mensagem que exibe o e-mail validado, garantindo que seja legível e visualmente agradável.
---

## Tecnologias

- Html5, CSS3 e Javascript




