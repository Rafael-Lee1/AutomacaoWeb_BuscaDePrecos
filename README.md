# Projeto Automacao Web - Busca de Precos
 <div>
<img src="http://img.shields.io/static/v1?label=STATUS&message=%20FINALIZADO&color=GREEN&style=for-the-badge"/>
</div>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/f06aea2585a5ebb7c97ff88c1e3ec42fe92502fbd897abe4bf2e56eb7039e1aa/68747470733a2f2f63646e2e69636f6e2d69636f6e732e636f6d2f69636f6e73322f3131322f504e472f3531322f707974686f6e5f31383839342e706e67"><img src="https://camo.githubusercontent.com/f06aea2585a5ebb7c97ff88c1e3ec42fe92502fbd897abe4bf2e56eb7039e1aa/68747470733a2f2f63646e2e69636f6e2d69636f6e732e636f6d2f69636f6e73322f3131322f504e472f3531322f707974686f6e5f31383839342e706e67" alt="python" width="40" height="40" data-canonical-src="https://cdn.icon-icons.com/icons2/112/PNG/512/python_18894.png" style="max-width: 100%;"></a></p>
<div>

 Automações web com Selenium para buscar informações na internet.

### Como vai funcionar:

- Imagina que você trabalha na área de compras de uma empresa e precisa fazer uma comparação de fornecedores para os seus insumos/produtos.

- Nessa hora, você vai constantemente buscar nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes.

- Seu objetivo: Se o valor dos produtos for abaixo de um preço limite definido por você, você vai descobrir os produtos mais baratos e atualizar isso em uma planilha.
- Em seguida, vai enviar um e-mail com a lista dos produtos abaixo do seu preço máximo de compra.

- No meu caso, vou fazer com produtos comuns em sites como Google Shopping e Buscapé, mas a ideia é a mesma para outros sites.

### Outra opção:

- APIs

### O que tenho disponível?

- Planilha de Produtos, com os nomes dos produtos, o preço máximo, o preço mínimo (para evitar produtos "errados" ou "baratos de mais para ser verdade" e os termos que vou querer evitar nas nossas buscas.

### O que devo fazer:

- Procurar cada produto no Google Shopping e pegar todos os resultados que tenham preço dentro da faixa e sejam os produtos corretos
- O mesmo para o Buscapé
- Enviar um e-mail para o seu e-mail (no caso da empresa seria para a área de compras por exemplo) com a notificação e a tabela com os itens e preços encontrados, junto com o link de compra. (Vou usar o e-mail seuemail@gmail.com. Use um e-mail seu para fazer os testes para ver se a mensagem está chegando)
