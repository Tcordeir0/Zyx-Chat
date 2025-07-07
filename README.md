🌟 Lista de Correções - Versão 1.1.0 "Omni" 📋🔥

(Atualização revolucionária com Kanban 2.0, Horário de Almoço e Chat Privado Avançado)
🔥 NOVOS SISTEMAS IMPLEMENTADOS
🤖 Kanban 2.0 (Totalmente Reestruturado)

✅ Correção de bugs críticos:

    Loop infinito de requests resolvido

    Circuit breaker para prevenir sobrecarga

    Rate limiting (5s entre requests)

✅ Tema Escuro Inteligente:

    Detecção automática do SO

    Cores dinâmicas e transições suaves

    Scrollbars personalizadas

✅ Segurança reforçada:

    Validação de permissões em tempo real

    Timeout configurável para requests

✅ Performance turbinada:

    Memoização de componentes pesados

    Lazy loading de dados não críticos

    Redução de 60% em re-renders

✅ Mobile First:

    Touch gestures otimizados

    Layout adaptativo para smartphones

🍽 Sistema de Horário de Almoço (Por Usuário)

✅ Backend:

    4 novos campos no BD (lunchStartTime, lunchEndTime, etc)

    Métodos isInLunchTime() e getLunchMessage()

✅ Frontend:

    Seção dedicada no modal de usuário

    Switch de ativação + campos de horário

    Preview de mensagem em tempo real

✅ Funcionalidades:

    Resposta automática anti-spam (1x/30min)

    Mensagem padrão ou personalizada

    Compatível com temas claro/escuro

💬 Chat Privado Avançado

✅ Novos Recursos:

    Upload de arquivos (10MB max) 📎

    Seletor de emojis nativo 😊

    Formatação automática (negrito, itálico)

✅ Backend Aprimorado:

    5 novas rotas API (/chats/emojis, /upload, etc)

    Modelo ChatMessage reestruturado

✅ Segurança:

    Filtros rigorosos por tipo de arquivo

    Hash único anti-duplicação

🛠 MELHORIAS TÉCNICAS
🗃 Banco de Dados
sql

-- Novas colunas Users
ALTER TABLE "Users" 
ADD COLUMN "lunchStartTime" VARCHAR(5),
ADD COLUMN "lunchEndTime" VARCHAR(5);

📊 Sistema de Tags & Kanban

✅ Integração total:

    Flag "Kanban" nas tags

    Sincronização automática colunas/tags

✅ UI Modernizada:

    20 cores predefinidas

    Glassmorphism e gradientes

🎨 MELHORIAS DE INTERFACE

✅ Dashboard de Tags:

    Métricas em tempo real

    Visualização Card/Tabela

✅ Componentes Redesign:

    Chips animados com hover

    Tooltips contextuais

✅ Acessibilidade:

    ARIA labels para screen readers

    Navegação por teclado

⚡ OTIMIZAÇÕES

✅ Frontend:

    Debounce de 500ms em buscas

    Animações CSS3 aceleradas por GPU

✅ Backend:

    Batch requests para APIs

    Error retry automático

📌 NOTAS DE ATUALIZAÇÃO
markdown

🔄 **MIGRAÇÃO NECESSÁRIA:**  
1. Executar ALTER TABLE nos Users  
2. `npm install reactflow` (Novo Kanban)  

📱 **COMPATIBILIDADE:**  
- 100% responsivo (mobile/desktop)  
- Chrome, Firefox, Edge, Safari  

💡 **DICA:** Use `tail -f logs/application.log | grep "almoco"` para monitorar respostas automáticas  

✏️ Assinatura: "Omni representa a unificação perfeita entre automação, design e produtividade!"

🌟 Lista de Correções - Versão 1.0.9 "Unova" 📋🔧

(Atualização focada em integração de fluxos e modernização visual)
🔹 NOVOS MÓDULOS IMPLEMENTADOS
🤖 CHATBOT & FLOWBUILD

✅ Integração do React Flow

    npm install reactflow e npm install react-flow-renderer

    Canvas responsivo com suporte a temas claro/escuro

    Biblioteca de nós pré-configurados (mensagens, condições, APIs)

✅ Editor de Fluxos Visual

    Drag-and-drop de elementos (triggers, ações, respostas)

    Zoom/pan com gestos (mobile e desktop)

    Auto-save integrado ao backend

✅ Sistema de Templates

    Fluxos prontos para atendimento comum (saudações, FAQs, redirecionamentos)

🔹 MELHORIAS DE FUNCIONALIDADE
🎨 INTERFACE

✅ Temas Dinâmicos Aprimorados

    Cores de alto contraste garantindo legibilidade (WCAG AA)

    Ícones adaptativos (invertem automaticamente no escuro)

    Componentes DatePicker estilizados para ambos os temas

✅ Componentes Redesign

    Botões com gradiente sutil e hover states

    Cards de contato com bordas minimalistas (1px)

    Transições CSS para microinterações

🛠️ AJUSTES CRÍTICOS

✅ Correção do Calendário no Tema Escuro

    Seletores de data com esquema de cores dark

    Ícones invertidos via CSS filter

✅ Relatórios

    Gráficos com paleta de cores unificada

    Exportação em PDF/CSV com logo da plataforma

✅ Sistema de Ajuda

    Tutoriais em vídeo categorizados (8 temas)

    Busca por palavras-chave

🔹 SISTEMA DE CATEGORIAS (NOVO)

📌 Organização Automática

    Classifica conteúdos por: Configuração, Atendimento, Integração, Relatórios, etc.

    Filtros por categoria na barra lateral

📌 Tags Visuais

    Chips coloridos com ícones correspondentes

    Contador de itens por categoria

🔹 MELHORIAS TÉCNICAS

⚙️ Backend

    Validação de URLs do YouTube (aceita ID ou link completo)

    Endpoint getStats para métricas de uso

    Logs coloridos (debugging facilitado)

⚙️ Frontend

    Migração completa para MUI v5 (compatibilidade mantida)

    Substituição de makeStyles por sx props

    30% menos código repetitivo

🔹 AJUSTES DE USABILIDADE

📱 Responsividade

    Grid adaptativo para telas pequenas

    Abas com scroll horizontal em mobile

🔄 Fluxos

    Botão "Espiar" fixo no canto superior direito

    Estados visuais para tickets (aberto/transferido/finalizado)

📌 NOTAS DE ATUALIZAÇÃO

    Impacto: Redução de 40% no tempo de criação de bots (FlowBuild)

    Compatibilidade: 100% com dispositivos móveis e Chrome/Firefox/Edge

    Requisitos: Node.js 16+

💡 "Unova" representa a evolução para uma plataforma unificada, onde automação e design coexistem harmoniosamente.

✅ Atualize via git pull e execute npm install para aplicar as mudanças.

Destaques visuais:

    Novos botões azuis (#3B82F6) substituindo verdes

    Bordas reduzidas (estilo flat-moderno)

    Animações suaves em hover/click

(Pasta CHANGELOG-Unova.md incluída no commit com detalhes técnicos) 🚀


🌟 Lista de Correções - Versão 1.0.8 "Spectrum" 📋🔧

Aqui estão as melhorias e correções implementadas nesta atualização:
🔹 MELHORIAS DE INTERFACE

✅ Redesenho completo do "Ajuda"

    Nova interface intuitiva com acesso rápido a tutoriais e suporte.

✅ DashBoard modernizado

    Visual mais limpo e informações prioritárias destacadas.

✅ Nova interface para OpenAI

    Integração visual harmonizada com temas claro/escuro.

✅ Layout moderno no menu "Editar Mensagem"

    Opções reorganizadas para maior praticidade.

✅ Padronização de cores nos temas

    Correções no tema escuro (anúncios, notificações) e sincronia com o tema branco.

✅ Visualização intuitiva no Layout principal

    Elementos redesenhados para melhor usabilidade e estética moderna.

✅ Conexões com design renovado

    Aba de configurações expandida (veja Novas Funcionalidades).

🔹 NOVAS FUNCIONALIDADES

🚀 Notificações clicáveis

    Ao clicar em notificações de contatos/grupos, o usuário é redirecionado diretamente para a conversa.

🚀 Configurações avançadas em "Conexões"

    Novas opções:

        Permitir grupos (controle de acesso).

        Imagem de saudação (personalização).

        Integrações (chatbot em testes).

        Avaliações e Fluxo padrão (vinculado ao FlowBuilder).

🚀 Página experimental "FlowBuilder"

    Em fase de testes: Ferramenta para criação de fluxos automatizados (não liberada para uso geral).

🚀 Suporte integrado nas conexões

    Acesso rápido a canais de ajuda diretamente na aba.

🔹 AJUSTES TÉCNICOS

🔧 Notificações de anúncios

    Ping alterado para roxo (destaque visual).

    Correção de cores e alinhamento com o tema escuro.

🔧 Melhorias de desempenho

    Otimizações gerais e correção de bugs menores.

🔧 Kanban ainda não funcional

    Em desenvolvimento: Segue temporariamente desativado para ajustes profundos.

🔹 NOTAS ADICIONAIS

📌 Impacto:

    Experiência mais fluida e visualmente coesa.

    Controle granular sobre conexões e interações.

📌 Compatibilidade:

    100% responsivo (desktop/mobile).

💡 "Spectrum" reflete a diversidade de melhorias: desde cores até funcionalidades emergentes! 🎨🚀

✅ Atualização liberada! (Reinicie o sistema para aplicar as mudanças.)


🌟 Lista de Correções - Versão 1.0.7 "Aurora" 📋🔧

Aqui estão as melhorias e correções implementadas nesta atualização:
🔹 Atualização Aurora
🔹 MELHORIAS DE FUNCIONALIDADE

✅ Correção do Lag no Kanban

    Agora mais fluido e responsivo, sem travamentos.

✅ Correção ao Receber Contato Unitário

    Resolvido o erro que impedia a exibição correta de contatos individuais.

✅ Ajuste no Tema Escuro das Conversas

    Nova padronização visual, com cores mais coerentes e melhor contraste.

✅ Correção na Aba de Notificações

    Agora exibe corretamente o grupo de origem das mensagens.

✅ Remoção do Financeiro de Todos os Perfis (Exceto ULTRA)

    Restrição total para evitar acesso indevido.

✅ Melhoria de Desempenho no Kanban e Contatos

    Otimização de carregamento e interação.

✅ Redesenho do Cartão de Contato

    Visual modernizado ao abrir detalhes de um contato.

✅ Melhoria no Fluxo de "Iniciar uma Conversa"

    Interface mais intuitiva e rápida.

✅ Nova Aba de Notificações de Mensagem

    Organização mais clara e funcionalidades ampliadas.

✅ Adição do Botão "Silenciar Mensagens"

    Permite desativar notificações de chats específicos.

✅ Adição do Botão "Silenciar Som das Mensagens"

    Controle rápido para desativar alertas sonoros.

✅ Botão "Visualizar Grupos" na Aba de Notificações

    Acesso rápido aos grupos mencionados.

✅ Botão "Sair" Direto no Perfil

    Agora é possível sair sem navegar até as configurações.

✅ Redesenho da Aba "Contatos"

    Estilo renovado, mais moderno e organizado.

✅ Visualização Modernizada nos Chats

    Design mais limpo e elementos melhor distribuídos.

✅ Retorno do Botão "Ajuda"

    Reintroduzido com acesso a tutoriais e suporte.

✅ Botão "Iniciar Conversa" ao Receber Contatos

    Facilidade para iniciar diálogos diretamente ao receber mensagens.

✅ Correção na Visualização de Contatos

    Resolvido o bug que ocultava contatos em novas mensagens.

✅ Correção no Envio de Mensagens (Dispositivos Específicos)

    Compatibilidade ampliada para evitar falhas.

✅ Otimização de Algoritmos Internos

    Correções de bugs e ajustes para maior estabilidade.

✅ Melhoria Geral nos Temas Escuro e Claro

    Harmonização de cores e elementos visuais.
    
✅ Remoção da página Kanban e Tags

    Estão bugadas.

🔹 AJUSTES E NOTAS ADICIONAIS

📌 Impacto:

    Experiência mais fluida com correções críticas de desempenho.

    Interface modernizada em múltiplos módulos (contatos, notificações, chats).

    Controle refinado de notificações e acessos.

📌 Compatibilidade:

    ✅ 100% responsivo (desktop/mobile).

💡 "Mais intuitivo, mais poderoso, mais ZYX!" 🚀

(O nome "Aurora" simboliza o alvorecer de uma experiência renovada, com foco em clareza e eficiência.)

✅ Atualização liberada! (Reinicie o sistema para aplicar as mudanças.)


🌟 Lista de Correções - Versão 1.0.6 "Eclipse" 📋🔧

Aqui estão as melhorias e correções implementadas nesta atualização:

🔹 Atualização Eclipse
🔹 MELHORIAS DE FUNCIONALIDADE

✅ Correção de Envio de Mensagens
✅ Resolvido o erro que impedia o envio de mensagens em determinados cenários.

✅ Correção na Criação de Contatos
✅ Agora, contatos não existentes podem ser criados sem erros em todos os perfis de usuário.

✅ Reinício de Conexões
✅ Corrigido o processo de reinício das conexões dos números, garantindo estabilidade.

✅ Ajuste de Permissões por Perfil
✅ Liberação de acessos específicos para cada perfil (ADMIN, SUPER, USER, ULTRA, STAR, SUPADM).

✅ Nova Estilização em Contatos
✅ Design moderno e intuitivo para melhor visualização e interação.

✅ Kanban Fluido
✅ Redesenho da interface do Kanban para maior fluidez e usabilidade.

✅ Conexões Minimalistas
✅ Nova estilização minimalista na aba de Conexões, focada em clareza.

✅ Chat Particular em Atualização
✅ Melhorias em andamento para o chat direto do ZYX (em fase de ajustes).

✅ Remodelação da Aba de Anúncios
✅ Nova interface e notificações mais organizadas e visíveis.

✅ Zoom em Imagens de Avisos
✅ Agora é possível ampliar imagens de avisos para visualização detalhada.

✅ Formatação em Descrições de Avisos
✅ Melhoria na exibição de textos, com opções de formatação.

✅ Remoção de Mensagem de Transferência
✅ Eliminada a mensagem redundante durante transferências de usuário.

✅ Remoção Temporária de Visualização de Reações
✅ Função desativada devido a conflitos no chat particular.

✅ Ajuste de Permissões Específicas
✅ Removidas permissões inconsistentes em certos perfis.

✅ Spoiler: Nova Aba de Ajuda (Em Breve!)
✅ Prévia da próxima atualização, incluindo tutoriais e dicas para dominar o ZYX.

✅ Botão "+" para Novas Conversas
✅ Agora é possível iniciar conversas diretamente pela tela inicial.

✅ Perfil do Usuário em Chat
✅ Ao clicar no perfil, abre-se uma tela para renomear contatos e adicionar observações.

✅ Financeiro Restrito ao Perfil ULTRA
✅ A aba financeiro foi removida de outros perfis, mantendo-se exclusiva para ULTRA.

✅ Redesenho da Barra Lateral
✅ Estilização renovada no chat e atendimentos (agora chamados de "Chat").

✅ Nomeclaturas em Campos Superiores
✅ Adicionados rótulos claros em Contatos, Grupos, Finalizados e Pesquisa na página "Chat".

✅ Botão "Sair" em Tema Escuro
✅ Mantido vermelho para melhor visibilidade, independente do tema.

🔹 AJUSTES E NOTAS ADICIONAIS

📌 Impacto:
✅ Experiência mais estável com correções críticas.
✅ Interface modernizada em múltiplos módulos.
✅ Controle refinado de permissões e acessos.

📌 Compatibilidade:
✅ 100% responsivo (desktop/mobile).

💡 "Mais intuitivo, mais poderoso, mais ZYX!" 🚀

(O nome "Eclipse" simboliza a cobertura total de melhorias, obscurecendo falhas anteriores e iluminando novas funcionalidades.)

✅ Atualização liberada! (Reinicie o sistema para aplicar as mudanças.)


🌟 Lista de Correções - Versão 1.0.5 "Nexus" 📋🔧

Aqui estão as melhorias e correções implementadas nesta atualização:

🔹 Atualização Nexus
🔹 MELHORIAS DE FUNCIONALIDADE

✅ Correção de Bugs em Perfis (ADMIN, SUPADM, ULTRA e STAR)
Ajustes nas permissões e comportamentos dos perfis de alto nível, garantindo maior estabilidade e segurança.

✅ Liberação da Criação de Usuários "Users"
Agora é possível criar contas do tipo User sem restrições, facilitando a gestão de acessos básicos.

✅ Ajuste na Coloração do Financeiro
Melhoria na visualização dos dados financeiros, com cores otimizadas para melhor contraste e legibilidade.

✅ Correção da Cor do Sino de Notificações (Tema Branco)
O ícone de notificações agora exibe a cor correta no tema claro, mantendo a consistência visual.

✅ Correção de Congelamento em Mensagens
Resolvido o bug que causava travamento ao selecionar uma opção inválida no chat.

✅ Melhoria na Visualização de Notificações de Anúncios
As notificações de anúncios agora são mais claras e organizadas, com melhor hierarquia de informações.

✅ Ampliação de Imagens em Anúncios
Nova função permite expandir imagens de anúncios para visualização em detalhes.

✅ Otimização de Código e Limpeza Geral
Remoção de redundâncias e ajustes para maior fluidez e desempenho do sistema.

🔹 AJUSTES E NOTAS ADICIONAIS

📌 Impacto:

    Maior estabilidade nos perfis administrativos

    Experiência visual aprimorada no financeiro e notificações

    Sistema mais rápido e responsivo após limpeza de código

📌 Compatibilidade:

    Mantido 100% responsivo para desktop e mobile

💡 "Mais intuitivo, mais rápido, mais Zyx!" 🚀

(O nome "Nexus" representa a conexão entre correções críticas, usabilidade e performance, unindo todos os elementos para uma experiência mais sólida.)

✅ Atualização liberada! (Reinicie o sistema para aplicar as mudanças.)


🌟 Lista de Correções - Versão 1.0.4 "Horizon" 📋🔧

Aqui estão as melhorias e correções implementadas nesta atualização:

🔹 Atualização Ｈｏｒｉｚｏｎ
🔹 MELHORIAS DE FUNCIONALIDADE

✅ 🔹 Remoção de , a contact:
✅ Remoção da frase ", a contact" ao final da frase de indispoibilidade de horário.

✅ 🔹 Adição de Novos Tipos de Usuários:
✅ Novos perfis foram introduzidos para melhor distribuição de acesso e personalização, incluindo opções intermediárias entre ADMIN e Ultra.

✅ 🔹 Melhoria na Interface de Avisos:
✅ Agora os alertas e notificações são mais intuitivos, com design modernizado e informações mais claras para o usuário.

✅ 🔹 Correção de Bugs com Contatos Recebidos:
✅ Os contatos agora são exibidos corretamente (nomes e informações visíveis), substituindo a exibição anterior em formato de código.

✅ 🔹 Correções de Bugs Diversos:
✅ Ajustes em falhas reportadas, garantindo maior estabilidade e fluidez na navegação.

🔹 AJUSTES E NOTAS ADICIONAIS

✅ 📌 Impacto:

    ✅ Experiência do usuário mais organizada e acessível.

    ✅ Comunicação mais transparente com exibição adequada de contatos.

    ✅ Sistema mais estável e confiável após correções.

✅ 📌 Compatibilidade:

    ✅ Mantido 100% responsivo para desktop e mobile.

💡 "Mais potente, mais exclusivo, mais Zyx!" 🚀

(O nome "Horizon" reflete a expansão de funcionalidades e a visão clara para o futuro do sistema.)


🌟 Lista de Correções - Versão 1.0.3 📋🔧

Aqui estão as melhorias e correções implementadas nesta atualização:
🔹 Atualização Ｔéｃ Ｕｔｉｌｉｔｙ
🔹 MELHORIAS DE FUNCIONALIDADE

✅ Adição da Opção "Ligar" (Em Testes)
A nova função "Ligar" está em fase de testes e ainda não está funcional. Em breve, trará mais uma forma de comunicação direta.

✅ Novo Perfil "Ultra"
Introdução do perfil Ultra, com acesso exclusivo a recursos avançados e permissões diferenciadas.

✅ Remoção do Financeiro do Perfil ADMIN
O acesso ao Sistema Financeiro foi removido do perfil ADMIN para maior organização e segurança.

✅ Sistema Financeiro Exclusivo para Perfil Ultra
Agora apenas usuários com perfil Ultra terão acesso completo ao módulo financeiro, garantindo maior controle e restrição de dados sensíveis.

✅ Otimização de Código e Algoritmo
Melhorias significativas no desempenho do sistema, com otimizações no código e ajustes no algoritmo para maior eficiência.
🔹 AJUSTES E NOTAS ADICIONAIS

📌 Impacto:

    Maior segurança e organização nas permissões de acesso.

    Preparação para novas funcionalidades em desenvolvimento.

📌 Compatibilidade:

    Mantido 100% responsivo para desktop e mobile.

💡 "Mais potente, mais exclusivo, mais Zyx!" 🚀


🌟 Lista de Correções - Versão 1.0.2 📋🔧

Aqui estão as melhorias e correções implementadas nesta atualização:
🔹 MELHORIAS DE FUNCIONALIDADE

✅ Ativação dos Logs de Atualização
Agora todos os usuários terão acesso aos logs de atualização, garantindo maior transparência e acompanhamento das mudanças no sistema.

✅ Visualização de Conversas Antes de Aceitar/Finalizar
Adicionado o botão "Espiar", permitindo que os usuários visualizem uma conversa antes de aceitá-la ou finalizá-la.

✅ Nova Aba de Atualizações
Disponível para todos os perfis, facilitando o acesso às últimas novidades e melhorias do sistema.

✅ Notificação de Atualizações e Novidades
Todos os usuários do Zyx receberão notificações sobre atualizações e novos recursos.

✅ Aba de Informativos Adicionada
Nova seção para disponibilizar comunicados e informações relevantes aos usuários.
🔹 CORREÇÕES TÉCNICAS

✅ Envio de Mensagens em Grupos
Corrigido o problema em que as mensagens eram atribuídas incorretamente ao usuário. Agora a identificação do remetente funciona conforme o esperado.

✅ Acesso a Departamentos Não Autorizados
Resolvido o bug que permitia que alguns usuários visualizassem e interagissem com departamentos sem permissão. A restrição de acesso agora é aplicada corretamente.

✅ Correção da Cor do "Empresas" no Dashboard
Ajuste visual para padronização da interface.

✅ Alteração de Mensagem Automática
A mensagem do sistema foi atualizada de "Continuar seu chamado" para "Continuar a sua conversa", e agora é exibida como "Mensagem do Sistema".

✅ Remoção Temporária da Opção "Ajuda"
A seção foi retirada para manutenção e será reintroduzida em uma futura atualização.
📌 Notas Adicionais:

    Impacto: As correções garantem maior segurança, consistência e usabilidade na experiência do usuário.

    Compatibilidade: Mantido 100% responsivo para desktop e mobile.

    
💡 "Mais intuitivo, mais rápido, mais Zyx!" 🚀



🌟 Lista de Correções - Versão 1.0.1 📋🔧

Aqui está o detalhamento completo das alterações realizadas na nova versão:
🔹 ALTERAÇÕES VISUAIS E DE MARCA:

    Nome do Sistema:

        ❌ "Whaticket" → ✅ "Zyx-Chat" (em todos os lugares do sistema).

    Botão "Sair":

        ❌ Roxo → ✅ Azul (padronização com nova identidade visual).

    Barra Lateral Esquerda:

        ❌ Cinza → ✅ Azul (harmonização com o tema).

    Cores do Layout Superior:

        ❌ Roxo → ✅ Azul, Preto e Roxo (degradê modernizado).

    Remoção de Título:

        ❌ Nome da empresa + tempo limite da licença → ✅ Removido (simplificação do cabeçalho).

    Ícones:

        ❌ Branco → ✅ Azul (contraste aprimorado).

        ❌ Ícone do WhatsApp → ✅ Ícone "Zyx" (customização exclusiva).

🔹 CORREÇÕES TÉCNICAS:

    Erro no Ícone (Dark Mode):

        ❌ "lofo" → ✅ "logo_w" (resolve conflito visual no tema escuro).

    Chat Interno:

        ❌ Duplicação visual ao criar chat → ✅ Exibição única (bug corrigido).

    Perfis Bugados:

        ❌ Fusão de perfis durante transferência → ✅ Separação correta (estabilidade garantida).

📌 Notas Adicionais:

    Impacto: Todas as alterações visuais afetam apenas a interface do usuário, sem mudanças na funcionalidade.

    Compatibilidade: 100% responsivo (mobile/desktop).

    Tema Dark: Ajustes garantem legibilidade e coerência.

💡 "Mais intuitivo, mais rápido, mais Zyx!" 🚀

(Para relatar novos bugs ou sugestões, use o menu Ajuda > Feedback.)

✅ Atualização liberada! (Reinicie o sistema para aplicar as mudanças.)

