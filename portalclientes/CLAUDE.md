# CLAUDE.md
# PORTAL DO CLIENTE — JAQUELINE FERREIRA ASSESSORIA CONTÁBIL

## 1. OBJETIVO DESTE PROJETO

Este repositório contém o Portal do Cliente da Jaqueline Ferreira
Assessoria Contábil.

O portal já existe, está publicado e já foi disponibilizado aos clientes.

A prioridade deste projeto é:

1. preservar o portal existente;
2. preservar a identidade visual já aprovada;
3. preservar a estrutura de pastas já criada;
4. criar novos departamentos, documentos e competências seguindo o padrão existente;
5. utilizar os documentos reais como fonte de informação;
6. nunca inventar informações.

Este projeto NÃO deve ser recriado do zero.

---

# 2. REGRA MAIS IMPORTANTE — NÃO RECRIAR O PORTAL

O portal existente é a referência oficial.

NÃO criar um novo sistema.

NÃO criar um novo layout.

NÃO substituir a estrutura existente por outra arquitetura.

NÃO criar um design diferente para cada departamento.

NÃO alterar a identidade visual por iniciativa própria.

NÃO substituir os arquivos HTML existentes simplesmente porque seria
mais fácil criar outro.

Sempre trabalhar a partir da estrutura já existente no repositório.

Se for necessário criar uma nova página, utilizar como referência
a página existente do mesmo nível ou do departamento mais semelhante.

---

# 3. ESTRUTURA OFICIAL

A estrutura atual segue a lógica:

CLIENTE
↓
DEPARTAMENTO
↓
DOCUMENTOS
↓
COMPETÊNCIA
↓
DOCUMENTOS DO PERÍODO

Exemplo:

portalclientes/
└── transjn/
    ├── index.html
    │
    └── fiscal/
        ├── index.html
        │
        └── documentos/
            ├── index.html
            │
            └── 09.2026/
                └── index.html

Esta estrutura já foi definida e deve ser preservada.

Não criar uma arquitetura alternativa.

---

# 4. FUNÇÃO DE CADA INDEX.HTML

Cada nível possui uma função própria.

## 4.1 CLIENTE

Exemplo:

transjn/index.html

É a página principal daquele cliente.

Ela apresenta os departamentos disponíveis.

---

## 4.2 DEPARTAMENTO

Exemplo:

transjn/fiscal/index.html

É a página do departamento Fiscal.

Ela deve seguir o padrão visual e estrutural já existente
nos demais departamentos do portal.

---

## 4.3 DOCUMENTOS

Exemplo:

transjn/fiscal/documentos/index.html

É a página de organização/acesso aos documentos daquele departamento.

---

## 4.4 COMPETÊNCIA

Exemplo:

transjn/fiscal/documentos/09.2026/index.html

É a página correspondente àquela competência/período.

Ela deve apresentar somente os documentos pertencentes àquela
competência.

---

# 5. REGRAS PARA CRIAÇÃO DE NOVOS MESES

Quando for necessário criar uma nova competência:

Exemplo:

09.2026
10.2026
11.2026

NÃO criar o novo HTML do zero.

Primeiro:

1. localizar a competência anterior;
2. abrir o index.html existente;
3. analisar sua estrutura;
4. utilizar essa página como referência;
5. criar a nova competência mantendo o mesmo padrão;
6. alterar somente o que for necessário para a nova competência;
7. atualizar os nomes e links dos documentos;
8. conferir todos os links.

Exemplo:

Se existir:

transjn/fiscal/documentos/09.2026/index.html

e for necessário criar:

transjn/fiscal/documentos/10.2026/index.html

utilizar o 09.2026 como referência.

NÃO criar um layout diferente para 10.2026.

---

# 6. REGRAS PARA NOVOS DEPARTAMENTOS

Quando for necessário criar um novo departamento:

1. analisar o index.html principal do cliente;
2. analisar os departamentos já existentes;
3. identificar o padrão visual;
4. identificar o padrão de navegação;
5. identificar o padrão de botões, cards, menus e links;
6. utilizar esse padrão;
7. criar somente o conteúdo específico do novo departamento.

Nunca criar um departamento com aparência de outro sistema.

---

# 7. DOCUMENTOS SÃO A FONTE DA VERDADE

Antes de criar ou atualizar uma página de documentos,
é OBRIGATÓRIO analisar os documentos disponíveis na pasta correspondente.

Não presumir quais documentos deveriam existir.

Não inventar documentos.

Não inventar nomes.

Não inventar valores.

Não inventar datas.

Não inventar competências.

Não inventar informações fiscais, contábeis ou trabalhistas.

A página deve refletir os documentos que realmente existem.

---

# 8. LEITURA DOS DOCUMENTOS

Antes de montar um index.html de uma competência:

1. verificar quais arquivos existem naquela pasta;
2. identificar o tipo de cada documento;
3. ler/analisar os documentos quando necessário;
4. identificar o nome correto;
5. identificar a competência;
6. identificar o período;
7. identificar informações relevantes para apresentação;
8. criar os links para os arquivos corretos.

Se um documento estiver presente, ele deve ser considerado.

Se um documento não estiver presente, não criar um botão ou link
como se ele existisse.

---

# 9. NÃO INVENTAR INFORMAÇÕES

Nunca preencher informações por suposição.

Se uma informação não estiver disponível:

- não inventar;
- não estimar;
- não completar automaticamente;
- não copiar informação de outro cliente.

Quando a informação for necessária e não estiver disponível,
sinalizar a ausência.

---

# 10. ISOLAMENTO ENTRE CLIENTES

Cada cliente possui seus próprios documentos.

NUNCA utilizar:

- documento de outro cliente;
- informação de outro cliente;
- link de outro cliente;
- nome de outro cliente;
- CNPJ de outro cliente;
- competência de outro cliente.

Antes de criar ou alterar um arquivo, confirmar que ele pertence
ao cliente correto.

Exemplo:

transjn/

não pode utilizar documentos de:

macaia/
melissa/
vedi/
ou qualquer outro cliente.

---

# 11. LINKS DOS DOCUMENTOS

Todos os links devem apontar para os arquivos reais existentes
no repositório.

Antes de criar um link:

1. verificar se o arquivo existe;
2. verificar o caminho;
3. verificar a extensão;
4. verificar se o caminho relativo está correto.

Nunca criar links fictícios.

Nunca criar links para arquivos que não existem.

---

# 12. CAMINHOS RELATIVOS

Ao criar links entre páginas HTML, utilizar caminhos relativos
compatíveis com a estrutura existente.

Sempre considerar o nível atual da página.

Exemplo:

Uma página dentro de:

cliente/fiscal/documentos/09.2026/

não deve utilizar automaticamente o mesmo caminho de uma página em:

cliente/

Os caminhos devem ser conferidos de acordo com a localização real
do arquivo.

---

# 13. IDENTIDADE VISUAL

A identidade visual existente do Portal do Cliente é considerada
APROVADA.

Preservar:

- cores;
- fontes;
- tamanhos;
- espaçamentos;
- cabeçalho;
- rodapé;
- botões;
- cards;
- ícones;
- bordas;
- sombras;
- menus;
- navegação;
- responsividade;
- estrutura visual.

Não alterar esses elementos sem autorização expressa da Jaqueline.

---

# 14. NÃO "MELHORAR" O DESIGN POR CONTA PRÓPRIA

Não alterar o design apenas porque existe uma preferência técnica
ou estética diferente.

Não modernizar.

Não redesenhar.

Não trocar cores.

Não trocar fontes.

Não reorganizar a interface.

Não transformar uma página existente em outro estilo.

Se houver uma oportunidade de melhoria visual, apresentar a sugestão
ANTES de alterar.

---

# 15. PRESERVAR O QUE JÁ ESTÁ FUNCIONANDO

Antes de alterar qualquer arquivo:

1. ler o arquivo atual;
2. entender sua função;
3. preservar o que já funciona;
4. alterar somente o necessário.

Nunca substituir um arquivo inteiro por uma versão simplificada
sem necessidade.

Nunca remover funcionalidades existentes sem autorização.

---

# 16. CRIAÇÃO DE NOVOS ARQUIVOS

Ao criar um novo arquivo:

1. verificar se já existe um arquivo semelhante;
2. utilizar o arquivo existente como referência;
3. preservar sua estrutura;
4. alterar apenas os dados necessários;
5. conferir os links;
6. conferir a navegação;
7. conferir o resultado final.

---

# 17. ALTERAÇÕES EM ARQUIVOS EXISTENTES

Não modificar arquivos existentes de forma ampla.

Antes de alterar:

- identificar exatamente o que precisa ser alterado;
- preservar todo o restante;
- não apagar conteúdo funcional;
- não recriar a página inteira sem necessidade.

---

# 18. DOCUMENTOS E HTML DEVEM SER SEPARADOS

Os documentos reais são a fonte de conteúdo.

Os arquivos HTML são a interface de apresentação.

Não misturar essas funções.

O HTML deve apresentar os documentos existentes de forma organizada.

O HTML não deve inventar documentos para preencher espaços.

---

# 19. PADRÃO DE NOMES

Manter os nomes de pastas já existentes.

Não renomear clientes.

Não renomear departamentos existentes.

Não alterar a estrutura de URLs já publicada.

Para competências, preservar o padrão já utilizado:

09.2026
10.2026
11.2026

etc.

---

# 20. COMPETÊNCIAS

Uma competência representa um período específico.

Os documentos de uma competência devem permanecer dentro
da respectiva pasta.

Exemplo:

fiscal/documentos/09.2026/

não deve receber documentos de 10.2026.

---

# 21. CHECKLIST ANTES DE FINALIZAR

Antes de considerar uma alteração concluída, verificar:

[ ] O cliente está correto?

[ ] O departamento está correto?

[ ] A competência está correta?

[ ] Os documentos realmente existem?

[ ] Os documentos foram analisados?

[ ] Os nomes dos documentos estão corretos?

[ ] Os links apontam para arquivos existentes?

[ ] Os caminhos relativos estão corretos?

[ ] O layout segue o padrão existente?

[ ] O index.html anterior foi preservado?

[ ] Nenhuma informação foi inventada?

[ ] Nenhum documento de outro cliente foi utilizado?

[ ] Nenhuma funcionalidade existente foi removida?

[ ] A navegação continua funcionando?

---

# 22. REGRA DE SEGURANÇA

Se houver dúvida sobre:

- qual arquivo utilizar;
- qual documento pertence ao cliente;
- qual competência utilizar;
- qual informação apresentar;
- qual estrutura seguir;
- qual layout utilizar;

NÃO assumir.

Primeiro analisar os arquivos existentes e as referências do projeto.

Se a dúvida permanecer e puder causar alteração estrutural,
informar a dúvida antes de modificar.

---

# 23. PRINCÍPIO FINAL

Este projeto NÃO é para criar novos portais.

Este projeto é para MANTER E EXPANDIR o Portal do Cliente existente.

Sempre seguir esta ordem:

LER O QUE JÁ EXISTE
↓
ENTENDER A ESTRUTURA
↓
LER OS DOCUMENTOS
↓
IDENTIFICAR O QUE PRECISA SER CRIADO
↓
REUTILIZAR O PADRÃO EXISTENTE
↓
CRIAR OU ALTERAR SOMENTE O NECESSÁRIO
↓
CONFERIR LINKS E DOCUMENTOS
↓
PRESERVAR O PORTAL

A regra principal é:

PRESERVAR O EXISTENTE + LER OS DOCUMENTOS + NÃO INVENTAR.
