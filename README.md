João Hector de Oliveira Fraga

1. **ESTRURURA BASE E SUBMISSAO**
    - O formulario esta contido dentro de uma tag '<main>', indicando o conteudo principal da pagina.
    - A tag '<form>' foi configurada com 'action="/cadastro"' e 'method="post"'.

2. **ACESSIBILIDADE**
    - Foi usado o atributo 'for' nas tags '<label>' apontando para o id dos inputs.
    - Os botoes do tipo *radio* foram agrupados utilizando '<fieldset>' e '<legend>'.
    - No campo CPF, a instrucao de preenchimento foi associada ao campo atraves do atributo 'aria-describedby="dica-cpf"'.

3. **VALIDACAO**
    - O atributo 'required' foi adicionado aos campos obrigatorios para bloquear o envio dos dados em branco.
    - O campo de e-mail utiliza 'type="email"', que valoriza o formato e aciona o teclado com "@" em dispositivos moveis.
    - O CPF nao utiliza 'type="number"'. Em vez disso foi configurado 'type="text"', 'inputmode="numeric"' e 'pattern="[0-9]{11}"' para manter os zeros a esquerda, validar os 11 digitos e abrir o teclado numero do celular. O 'placeholder' foi usado apenas como visual.

4. **USO DE BOTOES SEMANTICOS**
    - Para enviar e limpar o formulario, foram utilizados as tags semanticas '<button type="submit">' e '<button type="reset">'.
