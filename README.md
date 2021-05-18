# https://andre-voronhuk.github.io/loja/
## Link para o site implementado no GitHub-Pages



### abaixo algumas anotações sobre futuras atualizações:

banco:

  produto:

  id_produto
  id_usuario (o id de quem esta vendendo o produto)
  Imagem_produto (opcional)
  preço_produto
  titulo_produto
  descrição_produto (opcional)
  tamanho_produto (padrão: tamanho unico)
  cor_produto
  quantidade_produto (padrão 1)
  ---------------------------------------
  usuario:
  login_usuario
  senha_usuario
  id_usuario
  nome_usuario
  saldo_usuario (inicia em R$1200 para testes)
  nivel_usuario (usuario/administrador)
  telefone_usuario
  email_usuario
  --------------------------------------
  vendas:
  id_venda
  id_usuario
  id_produto
  data_hora_venda
  quantidade_venda
  desconto_venda (padrao 0)
  total_venda
  --------------------------------------
  carrinho:
  
  id_carrinho
  id_usuario
  id_produto
  quantidade_carrinho
  total_carrinho
  



