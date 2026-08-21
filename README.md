# Global Search – Power BI

**Encontre qualquer informação no seu relatório em segundos.**

O **Global Search** adiciona ao Power BI um **campo de busca inteligente e universal**, permitindo que o usuário localize dados rapidamente sem precisar saber onde procurar ou qual filtro usar.

Digite um valor, escolha a sugestão e o relatório se ajusta automaticamente.

---

## O que este visual entrega

- Busca unificada em **múltiplos campos ao mesmo tempo**
- Sugestões organizadas e fáceis de entender
- Aplicação de filtro imediata em todo o relatório
- Navegação mais simples, mesmo em modelos complexos
- Melhor experiência para usuários técnicos e não técnicos

---

## Como ele melhora a experiência do relatório

Relatórios crescem, acumulam campos e filtros e acabam ficando difíceis de navegar.  
O Global Search resolve isso ao oferecer **um único ponto de entrada para busca**, reduzindo cliques, erros e confusão.

O usuário não precisa:
- Saber em qual filtro o dado está
- Entender a estrutura do modelo
- Ajustar múltiplos slicers

Basta pesquisar.

---

## Exemplos de uso

- Digite um **código** e veja sugestões vindas de diferentes campos  
- Pesquise por um **nome** e encontre todas as ocorrências relevantes  
- Localize rapidamente um **identificador**, referência ou descrição  
- Use como ponto central de navegação em dashboards grandes  

Tudo em um único campo de busca.

---

## Por que escolher o Global Search

- Deixa o relatório mais limpo e organizado  
- Substitui vários filtros por uma única interação  
- Acelera a análise de dados  
- Reduz a curva de aprendizado do usuário final  
- Funciona com qualquer tipo de relatório  

---

## Personalização simples e nativa

O visual se integra ao painel de formatação do Power BI, permitindo ajustar:

- Selecionar temas pré-definidos
- Ajustar tamanhos e cores de texto, plano de fundo, bordas, entre outros estilos 
- Definir a quantidade de sugestões exibidas

Sem configurações complexas.

---

## 100% gratuito. Sem exceções.

Este visual é e sempre será:

- Totalmente gratuito  
- Sem planos pagos  
- Sem licenciamento  
- Sem limitações ocultas  
- Sem coleta de dados  
- Sem dependências externas  

Pode ser usado livremente em ambientes pessoais, corporativos e produtivos.

---

**Global Search**
_Uma forma mais simples, rápida e intuitiva de navegar pelos seus dados._

---

## Notas de atualização

### v2.0.0.0
- **Correção de filtros órfãos** — quando um campo era removido do visual em edição ao vivo, o filtro ativo correspondente podia continuar aplicado ao relatório mesmo sem aparecer mais na interface; agora ele é limpo automaticamente
- **Correção de seleção múltipla (Ctrl+Click)** — em cliques muito rápidos e sucessivos, dois valores diferentes do mesmo campo podiam gerar um identificador interno duplicado, fazendo a remoção de um filtro apagar outro por engano
- **Correção de identidade de campo** — campos de tabelas diferentes com o mesmo nome de exibição (ex.: duas colunas "ID") não são mais confundidos entre si na busca, na cascata de filtros e nas tags
- **Correção de filtros por data** — valores de campos de data agora são enviados ao Power BI no formato correto, evitando que o filtro não retornasse resultados ou exibisse um valor divergente do selecionado ao reabrir o relatório
- **Correção de paginação (Carregar mais)** — evita concatenar dados de origens diferentes quando o relatório é atualizado (ex.: por outro filtro) enquanto uma página adicional ainda está sendo carregada
- **Número da versão exibido na tela inicial** — agora aparece de forma discreta no rodapé, facilitando identificar qual versão está instalada

### v1.0.3.0
- **Selecionar todos por grupo** — novo botão no cabeçalho de cada grupo de sugestões permite selecionar todos os valores correspondentes de um campo com um único clique, sem precisar usar Ctrl+Click repetidamente
- **Suporte a até 25 campos simultâneos** — limite de colunas aumentado de 10 para 25
- **Correção i18n** — contador de resultados por grupo ("5 de 20") agora traduzido corretamente em inglês e espanhol
- **Correção acessibilidade** — rótulo da área de filtros ativos traduzido conforme o idioma configurado

### v1.0.2.0
- Modos de busca configuráveis: Contém, Começa com, Igual
- Normalização de acentos e diferenciação de maiúsculas/minúsculas
- Métricas de performance (diagnóstico)
- Acessibilidade completa (ARIA + teclado)