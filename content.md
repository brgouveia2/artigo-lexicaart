O que são Diretivas no Angular

Diretivas no Angular são como truques que usamos para dizer ao nosso aplicativo como se comportar. Imagine que você tem um livro de regras para um jogo e, com essas regras, você pode mudar o jeito que as coisas funcionam na tela do seu computador.

O que são Diretivas Estruturais

Diretivas estruturais são aquelas que podem fazer coisas aparecerem ou desaparecerem na tela. É como se você tivesse um mágico que pode fazer um chapéu aparecer ou sumir, dependendo do que está acontecendo no jogo. Elas mudam a estrutura do HTML, adicionando ou removendo partes conforme necessário.

Exemplos de Diretivas Estruturais com Código

Aqui está um exemplo de uma diretiva estrutural chamada *ngIf. Ela mostra algo apenas se a condição for verdadeira. Vamos imaginar que você só quer mostrar uma mensagem se você tiver um brinquedo favorito:


<div *ngIf="temBrinquedoFavorito">
  Olá, este é meu brinquedo favorito!
</div>
E uma outra chamada *ngFor que repete um elemento para cada item em uma lista. Imagine que você tem uma coleção de figurinhas e quer mostrar todas elas:


<ul>
  <li *ngFor="let figurinha of figurinhas">{{ figurinha }}</li>
</ul>
O que são Diretivas de Atributos
Diretivas de atributos são como óculos mágicos que mudam a aparência das coisas. Elas não fazem nada desaparecer ou aparecer, mas mudam como as coisas se parecem ou se comportam. É como mudar a cor de um carro ou colocar adesivos nele.

Exemplos de Diretivas de Atributos com Código
Aqui está um exemplo de ngClass, que adiciona classes CSS a um elemento para mudar sua aparência. Imagine que você quer que um botão fique verde se algo estiver ativo:


<div [ngClass]="{ 'ativo': estaAtivo }">
  Este div fica ativo ou inativo!
</div>
E um exemplo de ngStyle, que muda o estilo de um elemento. Digamos que você quer que o texto fique vermelho quando estiver com raiva:


<div [ngStyle]="{ 'color': corTexto }">
  Este texto muda de cor!
</div>

Chama nas redes sociais!
Gostou das dicas sobre Angular? Siga-me nas redes sociais para mais truques e tutoriais de programação incríveis! Vamos aprender juntos e dominar o Angular! Junte-se à nossa comunidade e fique por dentro das novidades.

Hashtags
#Angular #DesenvolvimentoWeb #AprendizadoDivertido