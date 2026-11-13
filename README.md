# Face_X-QmlProject
## arquivos pra colocar no qt design studio

### Estado atual

- A interface está pronta para integração com Python/PostgreSQL: os dados de exemplo (mock) foram removidos do QML e os modelos começam vazios.
- O Python preenche a tela chamando funções do item raiz: `definirOcorrencias(lista)`, `adicionarOcorrencia(obj)`, `definirCadastrados(lista)` e `definirHistorico(lista)`. Os campos esperados estão comentados no próprio QML.
- **Pendente:** avisar o back-end quando o operador confirmar/descartar uma ocorrência e quando mexer nos cadastros. Hoje essas ações só atualizam a memória do QML.
- A imagem de fundo é carregada de uma URL fixa no QML, então precisa de internet para aparecer.
