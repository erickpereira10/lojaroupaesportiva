# Minha Loja — Moda Esportiva

Site demonstrativo feito com HTML, CSS e JavaScript puro.

## Executar no VS Code
1. Extraia o ZIP.
2. Abra a pasta `minha_loja` no VS Code.
3. Instale a extensão **Live Server**.
4. Clique com o botão direito em `index.html` → **Open with Live Server**.

## Funcionalidades
- Página inicial responsiva com identidade esportiva.
- Catálogo, busca, categorias, abas e ordenação por preço/nome.
- Carrinho com alteração de quantidade e remoção.
- Finalização demonstrativa: baixa um arquivo `.txt` com resumo do pedido.
- Painel ADMIN para cadastrar, editar e excluir produtos.
- Upload local de imagem (limite de 1,5 MB por imagem).
- Dados salvos no `localStorage` do navegador.

## Limitações do modo local
- Não há servidor, login seguro, estoque compartilhado ou pagamento online.
- Os produtos só ficam salvos no navegador/dispositivo usado para cadastrar. Limpar os dados do navegador pode apagá-los.
- O botão ADMIN não tem senha, pois este é um protótipo local. Não publique assim para uso real.
- As imagens de exemplo são externas e precisam de internet.
- O resumo de pedido é baixado como arquivo; não é enviado automaticamente à loja.
- Firebase não foi incluído porque o requisito escolhido foi painel local.

## Antes de publicar
Para vender de verdade, implemente autenticação, banco de dados e armazenamento em nuvem, validação no servidor, política de privacidade e integração com um provedor de pagamentos. Nunca coloque segredos no JavaScript do navegador.

## Arquivos
- `index.html`: páginas e modais
- `style.css`: design e responsividade
- `script.js`: catálogo, carrinho e painel local
