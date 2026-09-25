# Auditoria Ética, Governança de IA e Checklist Final de Entregáveis

- **Projeto:** Fundamentos do Violão para Acompanhamento de Hinos Congregacionais
- **Curso:** Violão para Igrejas Evangélicas (Nível Iniciante)
- **Documento:** Relatório de Auditoria Ética e Validação Pedagógica

## 1. Riscos de Dados Pessoais e Estratégias de Anonimização

No desenvolvimento e na execução prática deste plano de aula em turmas eclesiásticas ou comunitárias, a coleta e o processamento de dados devem seguir rigorosamente a Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018).

### 1.1 Mapeamento de Riscos

- **Fichas de Inscrição e Diagnóstico Inicial:** Coleta desnecessária de dados sensíveis (ex.: endereço residencial completo, RG/CPF de alunos para oficinas gratuitas).
- **Gravação de Vídeo/Áudio para Avaliação Formativa:** Captura de imagem e som de alunos durante os exercícios práticos sem autorização prévia, podendo violar o direito de imagem (especialmente no caso de menores de idade).
- **Histórico de Desempenho e Dificuldades Motoras:** Registro e compartilhamento não autorizado de relatórios pedagógicos indicando limitações físicas, motoras ou de aprendizagem dos alunos.

### 1.2 Estratégias de Mitigação e Anonimização

- **Princípio da Minimização:** Coletar apenas nome, telefone de contato/WhatsApp (para avisos do curso) e, no caso de menores de idade, o nome e contato do responsável legal.
- **Pseudo-anonimização em Rubricas Pedagógicas:** Todas as matrizes de avaliação, registros de evolução e bancos de dados de prática devem utilizar identificadores genéricos (ex.: Aluno A, Aluno B, ou códigos como TURMA1-001), evitando associar dificuldades técnicas ao nome público do participante.
- **Termo de Consentimento Livre e Esclarecido (TCLE):** Implementar um formulário simples de autorização de uso de imagem e voz para fins estritamente pedagógicos ou de registro da comunidade, com opção explícita para o aluno (ou responsável) recusar sem prejuízo na participação do curso.
- **Descarte Seguro:** Dados de frequência e desempenho acumulados para a disciplina devem ser arquivados com acesso restrito ao professor e excluídos em até 12 meses após a conclusão do módulo.

## 2. Direitos Autorais e Propriedade Intelectual

A elaboração de materiais didáticos para acompanhamento musical eclesiástico exige clareza quanto ao status de direitos patrimoniais e morais do repertório e dos conteúdos gerados por IA.

## 2.1 Análise de Domínio Público do Repertório

- **Hinos Tradicionais (Harpa Cristã / Cantor Cristão):** A grande maioria dos hinos tradicionais utilizados (ex.: Santo, Santo, Santo de Reginald Heber / John B. Dykes, 1826) já se encontra em Domínio Público sob as legislações brasileira e internacional (Lei de Direitos Autorais nº 9.610/1998, que estabelece o domínio público 70 anos após a morte do autor/compositor).
- **Traduções e Arranjos Específicos:** Embora a melodia e letra originais possam ser de domínio público, arranjos comerciais contemporâneos ou traduções recentes podem estar protegidos. Nos materiais deste projeto, são utilizadas apenas cifras baseadas em melodias tradicionais e arranjos harmônicos diretos (simplificados), sem cópia de partituras/livros comerciais protegidos.

### 2.2 Atribuição Moral e Licenciamento dos Materiais do Curso

- **Citação Obrigatória:** Todos os hinos citados nas fichas de exercícios e materiais complementares incluem a devida atribuição aos compositores e letristas originais (ex.: "Música: John B. Dykes | Letra: Reginald Heber | Tradução: J. G. Rocha").
- **Licença de Uso do Material Didático:** Todo o repositório (README.md, planos de aula, tabelas e guias de treino) é disponibilizado sob a licença Creative Commons Atribuição-NãoComercial 4.0 Internacional (CC BY-NC 4.0). Isso garante que qualquer igreja ou educador possa reutilizar e adaptar o material, proibindo explicitamente sua venda comercial.

## 3. Análise de Vieses Pedagógicos e Culturais (e Alternativas)

Modelos de IA e materiais didáticos tradicionais frequentemente carregam vieses implícitos que podem limitar a inclusão e a representatividade no ambiente eclesiástico.

| Viés Identificado | Descrição do Risco | Proposta de Alternativa / Mitigação Pedagógica | 
|-------------------|--------------------|------------------------------------------------|
Viés de Estilo / Exclusão Denominacional | Foco exclusivo em uma única tradição musical (ex.: apenas hinos solenizados europeus/norte-americanos do século XIX), ignorando a diversidade rítmica da igreja brasileira. | **Alternativa:** Integrar ao longo do curso cânticos tradicionais de matriz regional brasileira (ex.: baião e guarânia eclesiásticos tradicionais), mantendo o rigor do nível iniciante.
Viés de Gênero na Linguagem e Exemplos | Utilização de linguagem no masculino genérico e exemplos históricos focados exclusivamente em instrumentistas homens. | **Alternativa:** Adotar linguagem inclusiva e neutra no material didático (ex.: "o estudante / a pessoa praticante") e destacar o papel histórico de compositoras, tradutoras e instrumentistas mulheres na hinologia.
Viés de Habilidade (Capacitismo) | Pressupor que todos os alunos possuem a mesma flexibilidade motora, tamanho de mãos ou capacidade auditiva inicial. | **Alternativa:** Implementação do Plano de Diferenciação para o Perfil A, que introduz acordes ancorados, fitas visuais nos trastes e batidas adaptadas com palhetas macias.
Viés Pedagógico de IA (Over-explaining) | Tendência da IA em gerar explicações teóricas excessivamente longas e complexas para alunos iniciantes. | **Alternativa:** Revisão humana (Human-in-the-Loop) para converter blocos de texto em tabelas, checklist e passos de treino de 5 minutos.

## 4. Registro de Transparência: Uso de IA Generativa e Revisão Humana

A tabela abaixo documenta a divisão de responsabilidades entre as ferramentas de IA e a mediação pedagógica humana durante a criação de todo o ecossistema do projeto:
```
+-----------------------------------------------------------------------------------+
|                            FLUXO HUMAN-IN-THE-LOOP                                |
|                                                                                   |
|  [ Prompt Humano ]  --->  [ Geração por IA ]  --->  [ Curadoria & Edição Humana ] |
|  (Direcionamento)        (Draft & Estrutura)        (Validação & Ajuste Fino)     |
+-----------------------------------------------------------------------------------+
```

## 4.1 Matriz detalhada de Contribuição por Componente

| Componente do Projeto | Ferramenta de IA Utilizada | Papel do Modelo de IA | Papel da Curadoria e Revisão Humana |
|-----------------------|----------------------------|-----------------------|-------------------------------------|
**Plano de Aula Principal (`Plano_de_Aula_IA.pdf/.docx`)** | ChatGPT (GPT-4o) | Geração do esqueleto pedagógico, divisão da cronologia de 60 min e redação dos objetivos operacionais. | Ajuste do tempo de prática (20 min em duplas), calibração da nomenclatura de cifras e remoção de termos do estilo *worship* contemporâneo. | 
**Plano de Diferenciação Pedagógica (`diferenciacao_pedagógica_aula1_violao.md`)** | Gemini 3 Flash | Elaboração das microetapas motoras para o Perfil A e desafios de transposição para o Perfil B. | Validação técnica da viabilidade motora dos acordes simplificados (`G` ancorado) e definição de BPMs seguros ($40{-}50 \text{ BPM}$).
**Material Complementar (`material_complementar_aula1_violao.md`)** | ChatGPT & Gemini 3 Flash | Criação do gabarito comentado, elaboração do texto introdutório sobre cifras e estruturação do exercício em dupla. | Revisão ortográfica, verificação da precisão teórica das questões e inserção dos alertas éticos de direitos autorais.
**Apresentação em Slides (`Apresentacao_Aula_IA.pptx`)** | Canva Education AI | Diagramação visual automatizada, sugestão de paleta de cores acessível e posicionamento de elementos visuais. | Seleção de imagens representativas, ajustes de hierarquia de texto e alinhamento do contraste visual para projeção. | 
**Internacionalização (Trecho em Inglês - CEFR A2)**| Gemini 3 FlashTradução e adaptação do resumo pedagógico para o nível A2 de proficiência em inglês. | Verificação de equivalência terminológica de termos musicais (ex.: *chords, fretboard, strumming pattern*).

## 5. Trecho de Internacionalização / Internationalization (English CEFR A2)

*[Assistido por IA / AI-Assisted]*

### Lesson Overview: Beginner Guitar for Traditional Church Music (CEFR A2 Level)

- **Context:** Lesson 1 of the course Acoustic Guitar for Evangelical Churches (Beginner Level). This lesson focuses on traditional church hymns (Christian Harp and traditional chorus) and does not include modern worship styles.
- **Duration:** 60 minutes.
- **Key Learning Objectives:**
    1. Read simple chord diagrams and musical letters (`G`, `C`, `D`, `Em`).
    2. Form basic chords cleanly with the left hand.
    3. Keep a steady strumming rhythm (`↓  ↓  ↓  ↓`) at 50–60 BPM to support congregational singing
- **Main Activity:** "The Unified Pulse" — A 20-minute pair exercise where one student keeps the rhythm while the second student practices chord transitions.
- **Assessment:** Practical observation using a simplified 3-level rubric (Beginning, Progressing, Proficient).

## 6. Checklist Final de Entregáveis e Conformidade

Abaixo encontra-se a verificação final de todos os requisitos pedagógicos, técnicos, formais e éticos previstos para a entrega do repositório:

- [x] Plano de aula completo estruturado em seções formais com a tag [Assistido por IA] devidamente aplicada em todas as partes geradas/refinadas por IA.
- [x] Materiais pedagógicos prontos: textos de apoio curto, folha de exercícios com gabarito comentado e atividade prática em dupla ("O Pulso Unificado").
- [x] Adaptação para 2 perfis distintos implementada: plano diferenciado com microetapas para o Perfil A (dificuldades motoras/rítmicas) e extensão para o Perfil B (iniciante avançado/liderança).
- [x] Tradução de trecho pedagógico para inglês (nível CEFR A2) incluída para garantir a internacionalização do repositório.
- [x] Apresentação visual de slides gerada (Apresentacao_Aula_IA.pptx), pronta para suporte visual em sala de aula.
- [x] README.md do repositório configurado com resumo pedagógico, links de acesso aos arquivos, tabela de ferramentas de IA e reflexão crítica final.
- [x] Padronização exata dos nomes de arquivos:
    - `Plano_de_Aula_IA.pdf` / `Plano_de_Aula_IA.docx`
    - `Apresentacao_Aula_IA.pptx`
    - `Reflexao_IA.pdf` / `Reflexao_IA.docx`
- [x] Conformidade ética e de autoria garantida: diretrizes de privacidade de dados (LGPD), verificação de domínio público do repertório tradicional, mitigação de vieses e rubrica de avaliação inclusiva.