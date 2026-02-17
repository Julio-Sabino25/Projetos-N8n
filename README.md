## Fluxos n8n

Aqui vão os fluxos que criei com o n8n. Cada arquivo .json está pronto pra importar.

### Como importar no n8n
1. Abra o n8n
2. Clique em "Import from File" ou "Import from Clipboard"
3. Selecione o .json ou cole o conteúdo
4. Salve e ative

### Fluxos disponíveis:
- ** 1º projeto em N8N: [analise-linha-planilha-groq.json]**  
  Lê planilha XLSX → Merge → filtra → Loop → AI Agent (Groq) analisa linha por linha → adiciona coluna "analise" → salva novo XLSX com resultados.

- ** 2º projeto: Automação de Relatórios por Filiais [Projeto analise de dados.json]**

O que faz: Lê múltiplos arquivos (Produtos, Clientes, Vendas), limpa duplicados, separa por região (SP/RJ/ES) e usa IA para gerar um e-mail executivo personalizado.

Destaque Técnico: Implementação de lógica de Merge para envio de e-mail com anexo dinâmico e uso de Loops para processamento em massa.

Diferencial: Diferente do projeto 1, aqui os dados são agregados para fornecer um contexto completo ao Agent de IA, resultando em análises muito mais precisas.

Mais fluxos serão adicionados, conforme evoluo nos estudos!!!
