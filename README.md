# 🏥 Portal de Protocolos Clínicos - UTI (Terapia Intensiva)

Um portal web moderno, rápido, responsivo e limpo para centralizar e organizar os links de diretrizes, rotinas, checklists e protocolos de conduta médica e multiprofissional dentro das Unidades de Terapia Intensiva.

---

## ✨ Funcionalidades Principais

1. **Visualizador Integrado com Retorno Rápido**:
   - Abra qualquer protocolo sem sair do portal.
   - Botão **`← Voltar aos Protocolos`** fixo no topo (ou aperte `Esc`).
   - Opção de abrir em nova aba (`↗`) caso prefira guias separadas.

2. **Organização em Índice Alfabético Numerado (A - Z)**:
   - Todos os protocolos são ordenados alfabeticamente com **numeração sequencial (`#01`, `#02`, `#03`...)**.
   - **Índice Clicável A-Z**: barra superior com letras do alfabeto para filtrar instantaneamente pela inicial (ex: clique em `D` para ver Desmame, `P` para PAV/Profilaxia). Letras com protocolos ficam destacadas com ponto indicador.
   - **Alternador de Visualização (Cards vs Lista / Índice)**:
     - *Modo Índice / Lista*: visual compacto em tabela médica, perfeito para consultas rápidas na UTI.
     - *Modo Cards*: visualização detalhada com resumo clínico e tags.
   - **Menu Dropdown de Especialidades**: substitui a antiga barra de rolagem horizontal por um seletor limpo com contagem de protocolos por especialidade.

3. **Segurança e Modo Somente Leitura (Público)**:
   - Qualquer pessoa com o link entra por padrão em **Modo Somente Leitura**: não vê botões de cadastro, edição ou exclusão.
   - Apenas o administrador autenticado com senha pode adicionar, editar ou excluir protocolos.
   - Acesso protegido por criptografia SHA-256 e atalho rápido (`Ctrl+Shift+A`).
   - Senha padrão inicial: `adminuti` (alterável diretamente no painel).

4. **Cadastro Livre e Flexível (Modo Administrador)**:
   - Adicione seus próprios links (Google Drive, intranet hospitalar, OneDrive, PDFs).
   - Crie as categorias que desejar (+ Criar Nova Categoria...).

5. **Publicação Direta no GitHub (1 Clique)**:
   - Botão **`Publicar no GitHub`** direto no topo para o Administrador.
   - Sincroniza e atualiza o arquivo `data.js` do repositório automaticamente pela API do GitHub, sem precisar baixar arquivos manualmente.

6. **Busca Instantânea em Tempo Real**:
   - Filtra por nome, patologia, drogas ou tags.
   - Pressione `/` no teclado em qualquer tela para focar na busca.

7. **Favoritos do Plantão (⭐)**:
   - Fixe os protocolos mais consultados no posto de UTI.

8. **Modo Escuro / Noturno**:
   - Conforto visual para plantões noturnos com 1 clique.
