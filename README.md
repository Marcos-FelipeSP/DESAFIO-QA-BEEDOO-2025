# DESAFIO-QA-BEEDOO-2025

# Objetivo
Criar User Story e casos de teste (sucesso e erro) para o módulo **Cursos** disponível em:

---
# Decisões Tomadas
- Foco nos fluxos principais do módulo: **Listar cursos**, **Cadastrar curso**, **Excluir curso**.
- Criação de cenários de sucesso e de erro com base nas observações práticas do comportamento da aplicação.
- Uso de **Gherkin** para legibilidade.
- Documentação dos casos de teste em planilha (Google Sheets).
- Gravação de evidências MP4 para comprovação dos testes manuais.

---
# User Story
**Título:** Gerenciar Cursos
**Como** usuário administrador.
**Quero** cadastrar, listar e excluir cursos com validações corretas.
**Para que** o catálogo de cursos seja consistente e o usuário receba feedback claro ao interagir com o sistema.

# Critérios de Aceitação
- Exibir mensagem “Nenhum curso cadastrado” se a lista estiver vazia.  
- Validar todos os campos obrigatórios.  
- Bloquear datas inválidas (início > fim).  
- Bloquear número de vagas negativo.  
- Confirmar exclusão e remover curso da lista.  
- Descrição truncada na listagem (melhoria UX).

---
# Bugs Identificados
| ID | Descrição | Severidade |
|----|------------|-------------|
| BUG-01 | Lista de cursos sem feedback quando vazia | Alta |
| BUG-02 | Exclusão não remove curso | Alta |
| BUG-03 | Campos vazios permitem criação | Alta |
| BUG-04 | Data início > Data fim não valida | Média-Alta |
| BUG-05 | Campo número de vagas aceita valores negativos | Alta |
| IMPR-01 | Descrição longa sem truncar | Média |

---
# Como Executar os Testes
1. Acesse o site: [Módulo de Cursos](https://creative-sherbet-a51eac.netlify.app/)
2. Siga os passos definidos na planilha (abaixo).  
3. Grave evidências dos testes em MP4.  
4. Suba os vídeos no Google Drive e adicione o link aqui.

---
# Links
- 🧾 **Planilha Google Sheets:** [[INSIRA O LINK AQUI]](https://docs.google.com/spreadsheets/d/1_EDpXH2t_RNEQIXNscWgUdmJochfzu4Yl8AaCVH3xbM/edit?usp=sharing)
- 🎥 **Evidências (Google Drive):** [[INSIRA O LINK AQUI]](https://drive.google.com/drive/folders/1k_mXhpHfGU1yOcGt_pJDeV_P12zt-GDv?usp=sharing)
