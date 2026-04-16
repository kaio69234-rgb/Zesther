// Ghost Bot - Enterprise Logic

// --- Command Data ---
const commands = [
    // --- SLASH COMMANDS ---
    // Moderação & Configuração (General)
    { name: "/addemoji", desc: "📝 [🎨] Adiciona um emoji ao servidor com um nome personalizado.", category: "utils", type: "slash" },
    { name: "/avisos-ghostm", desc: "📝 [🔒] Gerenciador de avisos oficiais (Dev Only).", category: "mod", type: "slash" },
    { name: "/backup-ghostmod", desc: "📝 [📑] Sistema de Backup e Restauração de Configurações", category: "config", type: "slash" },
    { name: "/ban", desc: "📝 [🔨] Aplica punição severa (Banimento) a um usuário.", category: "mod", type: "slash" },
    { name: "/boasvindas-logs", desc: "📝 [👋] Configura o sistema avançado de boas-vindas.", category: "config", type: "slash" },
    { name: "/check-perms", desc: "📝 [📚] Verifica as permissões de um usuário em um canal específico.", category: "mod", type: "slash" },
    { name: "/clear", desc: "📝 [🧹] Limpa mensagens em massa do canal.", category: "mod", type: "slash" },
    { name: "/config-logsmod", desc: "📝 [🏩] Abre o painel para configurar os canais de log de moderação.", category: "config", type: "slash" },
    { name: "/ghost-prefix", desc: "📝 [🚀] Gerencia o sistema de prefixo do bot.", category: "config", type: "slash" },
    { name: "/kick", desc: "📝 [👟] Remove (Expulsa) um usuário do servidor.", category: "mod", type: "slash" },
    { name: "/lock", desc: "📝 [🔒] Bloqueia o canal para evitar novas mensagens.", category: "mod", type: "slash" },
    { name: "/message-id", desc: "📝 [📑] Encontra e exibe detalhes de uma mensagem usando o seu ID.", category: "utils", type: "slash" },
    { name: "/mod-gerenciamento", desc: "📝 [💛] Painel Avançado de Gerenciamento do Servidor", category: "mod", type: "slash" },
    { name: "/move-all", desc: "📝 [🎵] Move todos os usuários de um canal de voz para outro.", category: "mod", type: "slash" },
    { name: "/mute", desc: "📝 [🔇] Silencia temporariamente um usuário (Timeout).", category: "mod", type: "slash" },
    { name: "/nuke", desc: "📝 [💥] Recria o canal para limpar todas as mensagens.", category: "mod", type: "slash" },
    { name: "/prefix-diversao", desc: "📝 [🎉] Configura sistemas de diversão", category: "config", type: "slash" },
    { name: "/prefix-economy", desc: "📝 [💰] Mostra informações do sistema de Economia.", category: "config", type: "slash" },
    { name: "/prefix-education", desc: "📝 [🧪] Mostra informações do sistema Educacional.", category: "config", type: "slash" },
    { name: "/prefix-games", desc: "📝 [🎮] Mostra informações do sistema de Games.", category: "config", type: "slash" },
    { name: "/prefix-musica", desc: "📝 [🎵] Mostra informações do sistema de música.", category: "config", type: "slash" },
    { name: "/prefix-pets", desc: "📝 [🐾] Mostra informações do sistema de Pets.", category: "config", type: "slash" },
    { name: "/prefix-rpg", desc: "📝 [🐉] Mostra informações do sistema de RPG.", category: "config", type: "slash" },
    { name: "/prefix-social", desc: "📝 [💖] Mostra informações do sistema Social.", category: "config", type: "slash" },
    { name: "/role-cleanup", desc: "📝 [💎] Lista todos os cargos que não estão sendo usados por nenhum membro.", category: "mod", type: "slash" },
    { name: "/say-embed", desc: "📝 [📣] Envia uma mensagem personalizada em formato de Embed em um canal.", category: "utils", type: "slash" },
    { name: "/slowmode", desc: "📝 [🐢] Define o modo lento (slowmode) do canal.", category: "mod", type: "slash" },
    { name: "/system-autofeedback", desc: "📝 [⭐] Painel de gerenciamento de Auto-Feedback.", category: "config", type: "slash" },
    { name: "/system-bateponto", desc: "📝 [⏰] Configura o sistema de Bate Ponto", category: "config", type: "slash" },
    { name: "/system-comunidade", desc: "📝 [👥] Painel de gerenciamento da Comunidade.", category: "config", type: "slash" },
    { name: "/system-content", desc: "📝 [📋] Gerencia o sistema de mensagens de texto personalizadas.", category: "config", type: "slash" },
    { name: "/system-embeds", desc: "📝 [🎨] Gerencia o sistema de embeds personalizadas.", category: "config", type: "slash" },
    { name: "/system-emojis", desc: "📝 [🎨] Gerencia os emojis do servidor.", category: "config", type: "slash" },
    { name: "/system-encomendas", desc: "📝 [🛒] Configuração completa do sistema de Vendas/Encomendas.", category: "config", type: "slash" },
    { name: "/system-entreterimento", desc: "📝 [🚀] Painel de Entretenimento e Gamificação.", category: "config", type: "slash" },
    { name: "/system-formulario", desc: "📝 [📝] Configura o sistema de formulários.", category: "config", type: "slash" },
    { name: "/system-gifs", desc: "📝 [🎬] Gerencia o envio automático de Gifs/Icons.", category: "config", type: "slash" },
    { name: "/system-keys", desc: "📝 [🔑] Configuração completa do sistema de Keys e Produtos.", category: "config", type: "slash" },
    { name: "/system-mod", desc: "📝 [🛡️] Abre o painel avançado de controle e automação de moderação.", category: "config", type: "slash" },
    { name: "/system-parcerias", desc: "📝 [🤝] Configuração completa do sistema de parcerias automáticas.", category: "config", type: "slash" },
    { name: "/system-permissoes", desc: "📝 [📚] Painel avançado de gerenciamento de permissões e logs.", category: "config", type: "slash" },
    { name: "/system-seguranca", desc: "📝 [📌] Painel completo de Segurança e Moderação.", category: "config", type: "slash" },
    { name: "/system-sorteio", desc: "📝 [🎉] Painel de gerenciamento de Sorteios.", category: "config", type: "slash" },
    { name: "/system-sugestoes", desc: "📝 [💡] Painel de gerenciamento de Sugestões.", category: "config", type: "slash" },
    { name: "/system-sugestoesv2", desc: "📝 [💡] Configura o sistema avançado de sugestões V2.", category: "config", type: "slash" },
    { name: "/system-ticketv1", desc: "📝 [🎫] Painel completo para gerenciamento avançado de Tickets V1.", category: "config", type: "slash" },
    { name: "/system-ticketv2", desc: "📝 [🎫] Painel de configuração e gerenciamento de Tickets V2.", category: "config", type: "slash" },
    { name: "/system-utilidades", desc: "📝 [📋] Configura sistemas utilitários.", category: "config", type: "slash" },
    { name: "/system-verify", desc: "📝 [✅] Painel de controle e personalização do sistema de Verificação.", category: "config", type: "slash" },
    { name: "/system-verifyv2", desc: "📝 [✅] Configura o sistema de Verificação V2", category: "config", type: "slash" },
    { name: "/unban", desc: "📝 [🤝] Revoga o banimento de um usuário.", category: "mod", type: "slash" },
    { name: "/unlock", desc: "📝 [🔓] Desbloqueia o canal para permitir mensagens.", category: "mod", type: "slash" },
    { name: "/unmute-all", desc: "📝 [🚨] Remove o timeout de TODOS os membros mutados.", category: "mod", type: "slash" },
    { name: "/unmute", desc: "📝 [🔊] Remove o silenciamento de um usuário.", category: "mod", type: "slash" },

    // Discord
    { name: "/ghost-discord", desc: "📝 [👻] Comandos focados em obter informações do servidor.", category: "discord", type: "slash" },

    // Diversão
    { name: "/ghost-diversao", desc: "📝 [🎮] Acessa o menu de diversão e minigames.", category: "fun", type: "slash" },

    // Economia
    { name: "/ghost-economia", desc: "📝 [💰] Menu interativo para acessar todas as funcionalidades financeiras.", category: "eco", type: "slash" },

    // Imagens
    { name: "/ghost-imagens", desc: "📝 [🖼️] Acessa o menu completo de manipulação de imagens e memes.", category: "img", type: "slash" },
    { name: "/ghost-removerfundo", desc: "📝 [📕] Remove o fundo de uma imagem.", category: "img", type: "slash" },

    // Loja
    { name: "/comprar-gerar-pagamento", desc: "📝 [💰] Gerar um pagamento ou sacar saldo (Admin)", category: "shop", type: "slash" },
    { name: "/gerenciamento-vendasghost", desc: "📝 [📊] Gerencia as vendas da loja", category: "shop", type: "slash" },
    { name: "/comprar-loja", desc: "📝 [🏪] Abre a loja oficial do bot", category: "shop", type: "slash" },
    { name: "/vip-ghostmod", desc: "📝 [💎] Adquira o VIP Ghost Mod e tenha benefícios exclusivos!", category: "shop", type: "slash" },

    // Minecraft
    { name: "/ghost-minecraft", desc: "📝 [🧱] Ferramentas e utilitários para Minecraft.", category: "minecraft", type: "slash" },

    // Social
    { name: "/ghost-social", desc: "📝 [🤝] Central de interações sociais, perfil, casamento e reputação.", category: "social", type: "slash" },

    // Usuários
    { name: "/avatar", desc: "📝 [📸] Exibe o avatar de um usuário em alta qualidade.", category: "users", type: "slash" },
    { name: "/banner", desc: "📝 [🚩] Exibe o banner de um usuário em alta qualidade.", category: "users", type: "slash" },
    { name: "/botinfo", desc: "📝 [🤖] Estatísticas e informações detalhadas do sistema.", category: "users", type: "slash" },
    { name: "/emoji", desc: "📝 [✨] Análise detalhada de emojis customizados.", category: "users", type: "slash" },
    { name: "/roleinfo", desc: "📝 [📗] Informações completas e permissões de um cargo.", category: "users", type: "slash" },
    { name: "/servericon", desc: "📝 [🏰] Exibe e permite baixar o ícone do servidor.", category: "users", type: "slash" },
    { name: "/serverinfo", desc: "📝 [📊] Estatísticas e informações completas do servidor.", category: "users", type: "slash" },
    { name: "/userinfo", desc: "📝 [👤] Informações detalhadas e status de um usuário.", category: "users", type: "slash" },

    // Utilidade
    { name: "/comandos-membros", desc: "📝 [🚀] Mostra todos os comandos disponíveis para membros.", category: "utils", type: "slash" },
    { name: "/ghost-utilitarios", desc: "📝 [🎁] Ferramentas e recursos para informações e automação.", category: "utils", type: "slash" },
    { name: "/notificacoes-streaming", desc: "📝 [📡] Configura notificações de streaming.", category: "utils", type: "slash" },
    { name: "/ticket-premiumia", desc: "📝 [🧠] Gerenciamento avançado do sistema de Ticket com IA.", category: "utils", type: "slash" },
    { name: "/video-tiktok", desc: "📝 [🎥] Baixa vídeo do TikTok sem marca d'água e envia na DM.", category: "utils", type: "slash" },

    // Previews (Guides)
    { name: "/preview-vip", desc: "📝 [💎] Mostra vantagens de ser VIP, preços e como adquirir.", category: "shop", type: "slash" },
    { name: "/preview-staff", desc: "📝 [🛡️] Explica recrutamento, requisitos e hierarquia da Staff.", category: "mod", type: "slash" },
    { name: "/preview-parcerias", desc: "📝 [🤝] Detalha requisitos para fechar parceria com o servidor.", category: "config", type: "slash" },
    { name: "/preview-bot", desc: "📝 [🤖] Guia rápido sobre as principais funcionalidades do bot.", category: "utils", type: "slash" },
    { name: "/preview-xp", desc: "📝 [🏆] Explica sistema de níveis, recompensas e ranking.", category: "fun", type: "slash" },
    { name: "/preview-sonhos", desc: "📝 [💰] Guia Completo e Visual para o sistema de economia (Sonhos).", category: "eco", type: "slash" },

    // --- PREFIX COMMANDS (g!) ---
    // Administrador
    { name: "g!configprefix", desc: "📝 [⚙️] Altera o prefixo do bot (Simulação).", category: "admin", type: "prefix" },
    { name: "g!setprefix", desc: "📝 [⚙️] Altera o prefixo do bot (Alias).", category: "admin", type: "prefix" },
    { name: "g!giverole", desc: "📝 [🛡️] Dá um cargo a um usuário.", category: "admin", type: "prefix" },
    { name: "g!darcargo", desc: "📝 [🛡️] Dá um cargo a um usuário (Alias).", category: "admin", type: "prefix" },
    { name: "g!massban", desc: "📝 [🔨] Bane múltiplos usuários por ID.", category: "admin", type: "prefix" },
    { name: "g!banemmassa", desc: "📝 [🔨] Bane múltiplos usuários por ID (Alias).", category: "admin", type: "prefix" },
    { name: "g!removespam", desc: "📝 [🛡️] Ativa modo de segurança máxima temporariamente.", category: "admin", type: "prefix" },
    { name: "g!antiraid", desc: "📝 [🛡️] Ativa modo de segurança máxima temporariamente (Alias).", category: "admin", type: "prefix" },
    { name: "g!sayembed", desc: "📝 [💬] Envia uma mensagem em embed.", category: "admin", type: "prefix" },
    { name: "g!falar-embed", desc: "📝 [💬] Envia uma mensagem em embed (Alias).", category: "admin", type: "prefix" },
    { name: "g!takerole", desc: "📝 [⛔] Remove um cargo de um usuário.", category: "admin", type: "prefix" },
    { name: "g!removercargo", desc: "📝 [⛔] Remove um cargo de um usuário (Alias).", category: "admin", type: "prefix" },
    { name: "g!warn", desc: "📝 [⚠️] Adverte um usuário no servidor.", category: "admin", type: "prefix" },
    { name: "g!aviso", desc: "📝 [⚠️] Adverte um usuário no servidor (Alias).", category: "admin", type: "prefix" },
    { name: "g!advertir", desc: "📝 [⚠️] Adverte um usuário no servidor (Alias).", category: "admin", type: "prefix" },

    // Diversão
    { name: "g!8ball", desc: "📝 [🎱] Responde sua pergunta.", category: "fun", type: "prefix" },
    { name: "g!bola8", desc: "📝 [🎱] Responde sua pergunta (Alias).", category: "fun", type: "prefix" },
    { name: "g!pergunta", desc: "📝 [🎱] Responde sua pergunta (Alias).", category: "fun", type: "prefix" },
    { name: "g!attack", desc: "📝 [⚔️] Ataca um usuário.", category: "fun", type: "prefix" },
    { name: "g!atacar", desc: "📝 [⚔️] Ataca um usuário (Alias).", category: "fun", type: "prefix" },
    { name: "g!avatar", desc: "📝 [🖼️] Mostra o avatar do usuário.", category: "fun", type: "prefix" },
    { name: "g!av", desc: "📝 [🖼️] Mostra o avatar do usuário (Alias).", category: "fun", type: "prefix" },
    { name: "g!connect4", desc: "📝 [🎮] Jogue Quatro em Linha contra outro usuário.", category: "fun", type: "prefix" },
    { name: "g!c4", desc: "📝 [🎮] Jogue Quatro em Linha (Alias).", category: "fun", type: "prefix" },
    { name: "g!daily", desc: "📝 [💰] Coleta a recompensa diária.", category: "fun", type: "prefix" },
    { name: "g!diario", desc: "📝 [💰] Coleta a recompensa diária (Alias).", category: "fun", type: "prefix" },
    { name: "g!flip", desc: "📝 [🪙] Joga uma moeda.", category: "fun", type: "prefix" },
    { name: "g!moeda", desc: "📝 [🪙] Joga uma moeda (Alias).", category: "fun", type: "prefix" },
    { name: "g!fun_text", desc: "📝 [📝] Comandos de texto divertidos.", category: "fun", type: "prefix" },
    { name: "g!akinator", desc: "📝 [🧞] Jogue Akinator no Discord.", category: "fun", type: "prefix" },
    { name: "g!games_arcade", desc: "📝 [🕹️] Jogos Arcade variados (Gamecord).", category: "fun", type: "prefix" },
    { name: "g!games_board", desc: "📝 [🎲] Jogos de tabuleiro.", category: "fun", type: "prefix" },
    { name: "g!games_party", desc: "📝 [🎉] Jogos de festa e sorte.", category: "fun", type: "prefix" },
    { name: "g!games_quiz", desc: "📝 [🧠] Jogos de quiz e conhecimento.", category: "fun", type: "prefix" },
    { name: "g!hangman", desc: "📝 [😵] Jogue o jogo da forca.", category: "fun", type: "prefix" },
    { name: "g!forca", desc: "📝 [😵] Jogue o jogo da forca (Alias).", category: "fun", type: "prefix" },
    { name: "g!jokenpo", desc: "📝 [✂️] Joga Pedra, Papel e Tesoura.", category: "fun", type: "prefix" },
    { name: "g!ppt", desc: "📝 [✂️] Joga Pedra, Papel e Tesoura (Alias).", category: "fun", type: "prefix" },

    { name: "g!memory", desc: "📝 [🧠] Jogue o Jogo da Memória.", category: "fun", type: "prefix" },
    { name: "g!memoria", desc: "📝 [🧠] Jogue o Jogo da Memória (Alias).", category: "fun", type: "prefix" },
    { name: "g!money", desc: "📝 [💰] Mostra seu saldo.", category: "fun", type: "prefix" },
    { name: "g!saldo", desc: "📝 [💰] Mostra seu saldo (Alias).", category: "fun", type: "prefix" },
    { name: "g!rank", desc: "📝 [🌟] Mostra o nível e XP do usuário.", category: "fun", type: "prefix" },
    { name: "g!nivel", desc: "📝 [🌟] Mostra o nível e XP do usuário (Alias).", category: "fun", type: "prefix" },
    { name: "g!say", desc: "📝 [🗣️] Faz o bot repetir a mensagem.", category: "fun", type: "prefix" },
    { name: "g!falar", desc: "📝 [🗣️] Faz o bot repetir a mensagem (Alias).", category: "fun", type: "prefix" },
    { name: "g!serverinfo", desc: "📝 [ℹ️] Mostra informações do servidor.", category: "fun", type: "prefix" },
    { name: "g!si", desc: "📝 [ℹ️] Mostra informações do servidor (Alias).", category: "fun", type: "prefix" },
    { name: "g!ship", desc: "📝 [💘] Calcula a compatibilidade.", category: "fun", type: "prefix" },
    { name: "g!shippar", desc: "📝 [💘] Calcula a compatibilidade (Alias).", category: "fun", type: "prefix" },
    { name: "g!slap", desc: "📝 [👋] Dá um tapa em um usuário.", category: "fun", type: "prefix" },
    { name: "g!tapa", desc: "📝 [👋] Dá um tapa em um usuário (Alias).", category: "fun", type: "prefix" },
    { name: "g!tictactoe", desc: "📝 [🎮] Jogue Jogo da Velha contra outro usuário.", category: "fun", type: "prefix" },
    { name: "g!velha", desc: "📝 [🎮] Jogue Jogo da Velha (Alias).", category: "fun", type: "prefix" },
    { name: "g!tiodopave", desc: "📝 [🤡] Conta uma piada de tio do pavê.", category: "fun", type: "prefix" },
    { name: "g!piada", desc: "📝 [🤡] Conta uma piada de tio do pavê (Alias).", category: "fun", type: "prefix" },
    { name: "g!top", desc: "📝 [🏆] Mostra o ranking de XP.", category: "fun", type: "prefix" },
    { name: "g!leaderboard", desc: "📝 [🏆] Mostra o ranking de XP (Alias).", category: "fun", type: "prefix" },
    { name: "g!tretanews", desc: "📝 [📰] Cria uma manchete do Treta News.", category: "fun", type: "prefix" },
    { name: "g!treta", desc: "📝 [📰] Cria uma manchete do Treta News (Alias).", category: "fun", type: "prefix" },
    { name: "g!userinfo", desc: "📝 [👤] Mostra informações do usuário.", category: "fun", type: "prefix" },
    { name: "g!ui", desc: "📝 [👤] Mostra informações do usuário (Alias).", category: "fun", type: "prefix" },

    // Economia
    { name: "g!atm", desc: "📝 [🏦] Verifica o saldo bancário.", category: "eco", type: "prefix" },
    { name: "g!bal", desc: "📝 [🏦] Verifica o saldo bancário (Alias).", category: "eco", type: "prefix" },
    { name: "g!economy_actions", desc: "📝 [💸] Ações de economia (crime, rob, deposit, etc).", category: "eco", type: "prefix" },
    { name: "g!economy_advanced", desc: "📝 [📈] Economia avançada (stock, crypto, lottery).", category: "eco", type: "prefix" },
    { name: "g!economy_games", desc: "📝 [🎰] Jogos de aposta (slots, roulette, blackjack).", category: "eco", type: "prefix" },
    { name: "g!pay", desc: "📝 [💸] Transfere dinheiro para outro usuário.", category: "eco", type: "prefix" },
    { name: "g!pagar", desc: "📝 [💸] Transfere dinheiro para outro usuário (Alias).", category: "eco", type: "prefix" },
    { name: "g!work", desc: "📝 [💼] Trabalha para ganhar dinheiro.", category: "eco", type: "prefix" },
    { name: "g!trabalhar", desc: "📝 [💼] Trabalha para ganhar dinheiro (Alias).", category: "eco", type: "prefix" },

    // Imagem
    { name: "g!deepfry", desc: "📝 [🍟] Aplica o efeito Deep Fry.", category: "img", type: "prefix" },
    { name: "g!fritar", desc: "📝 [🍟] Aplica o efeito Deep Fry (Alias).", category: "img", type: "prefix" },
    { name: "g!fakesocial", desc: "📝 [📱] Gera imagens fake de redes sociais.", category: "img", type: "prefix" },
    { name: "g!filters", desc: "📝 [🎨] Aplica vários filtros em imagens.", category: "img", type: "prefix" },
    { name: "g!invert", desc: "📝 [🔄] Inverte as cores da imagem.", category: "img", type: "prefix" },
    { name: "g!negativo", desc: "📝 [🔄] Inverte as cores da imagem (Alias).", category: "img", type: "prefix" },
    { name: "g!jail", desc: "📝 [🚔] Coloca o usuário atrás das grades.", category: "img", type: "prefix" },
    { name: "g!preso", desc: "📝 [🚔] Coloca o usuário atrás das grades (Alias).", category: "img", type: "prefix" },
    { name: "g!memes", desc: "📝 [😂] Gera memes e efeitos variados.", category: "img", type: "prefix" },
    { name: "g!minecraft", desc: "📝 [🧱] Gera uma conquista ou desafio do Minecraft.", category: "img", type: "prefix" },
    { name: "g!achievement", desc: "📝 [🧱] Gera uma conquista ou desafio do Minecraft (Alias).", category: "img", type: "prefix" },
    { name: "g!neonify", desc: "📝 [✨] Escreve texto em neon.", category: "img", type: "prefix" },
    { name: "g!overlays", desc: "📝 [🖼️] Aplica overlays variados.", category: "img", type: "prefix" },
    { name: "g!popcat_images", desc: "📝 [🐱] Gera memes e imagens variadas (Pack Popcat).", category: "img", type: "prefix" },
    { name: "g!resize", desc: "📝 [🖼️] Redimensiona a imagem do avatar.", category: "img", type: "prefix" },
    { name: "g!redimensionar", desc: "📝 [🖼️] Redimensiona a imagem do avatar (Alias).", category: "img", type: "prefix" },
    { name: "g!textgen", desc: "📝 [📝] Gera imagens com texto.", category: "img", type: "prefix" },
    { name: "g!triggered", desc: "📝 [😤] Aplica o efeito Triggered na foto de perfil.", category: "img", type: "prefix" },
    { name: "g!pistola", desc: "📝 [😤] Aplica o efeito Triggered na foto de perfil (Alias).", category: "img", type: "prefix" },
    { name: "g!wanted", desc: "📝 [🤠] Aplica o efeito de cartaz de procurado.", category: "img", type: "prefix" },
    { name: "g!procurado", desc: "📝 [🤠] Aplica o efeito de cartaz de procurado (Alias).", category: "img", type: "prefix" },
    { name: "g!wasted", desc: "📝 [☠️] Aplica o efeito Wasted do GTA.", category: "img", type: "prefix" },
    { name: "g!gta", desc: "📝 [☠️] Aplica o efeito Wasted do GTA (Alias).", category: "img", type: "prefix" },

    // Música
    { name: "g!music_extra", desc: "📝 [🎵] Comandos extras de música (lyrics, filters).", category: "music", type: "prefix" },
    { name: "g!nowplaying", desc: "📝 [▶️] Mostra a música atual.", category: "music", type: "prefix" },
    { name: "g!np", desc: "📝 [▶️] Mostra a música atual (Alias).", category: "music", type: "prefix" },
    { name: "g!play", desc: "📝 [▶️] Toca uma música.", category: "music", type: "prefix" },
    { name: "g!p", desc: "📝 [▶️] Toca uma música (Alias).", category: "music", type: "prefix" },
    { name: "g!queue", desc: "📝 [📜] Mostra a fila de músicas.", category: "music", type: "prefix" },
    { name: "g!q", desc: "📝 [📜] Mostra a fila de músicas (Alias).", category: "music", type: "prefix" },
    { name: "g!skip", desc: "📝 [⏭️] Pula a música atual.", category: "music", type: "prefix" },
    { name: "g!sk", desc: "📝 [⏭️] Pula a música atual (Alias).", category: "music", type: "prefix" },
    { name: "g!stop", desc: "📝 [🛑] Para a música e sai do canal.", category: "music", type: "prefix" },
    { name: "g!st", desc: "📝 [🛑] Para a música e sai do canal (Alias).", category: "music", type: "prefix" },
    { name: "g!volume", desc: "📝 [🔊] Altera o volume da música.", category: "music", type: "prefix" },
    { name: "g!vol", desc: "📝 [🔊] Altera o volume da música (Alias).", category: "music", type: "prefix" },

    // Pets
    { name: "g!pets", desc: "📝 [🐾] Sistema completo de Pets.", category: "pets", type: "prefix" },
    { name: "g!pets_battle", desc: "📝 [⚔️] Batalhas e captura de Pets.", category: "pets", type: "prefix" },
    { name: "g!pets_info", desc: "📝 [ℹ️] Informações e exploração de pets.", category: "pets", type: "prefix" },
    { name: "g!pets_shop", desc: "📝 [🏪] Loja de itens para pets.", category: "pets", type: "prefix" },
    { name: "g!pets_social", desc: "📝 [💕] Comandos sociais de pets.", category: "pets", type: "prefix" },

    // RPG
    { name: "g!rpg_adventure", desc: "📝 [⚔️] Aventuras e combate do RPG.", category: "rpg", type: "prefix" },
    { name: "g!rpg_core", desc: "📝 [📜] Comandos principais do RPG.", category: "rpg", type: "prefix" },
    { name: "g!rpg_items", desc: "📝 [🎒] Comandos de itens e economia do RPG.", category: "rpg", type: "prefix" },
    { name: "g!rpg_social", desc: "📝 [🤝] Comandos sociais e de habilidades do RPG.", category: "rpg", type: "prefix" },

    // Social
    { name: "g!hug", desc: "📝 [🤗] Dê um abraço em alguém.", category: "social", type: "prefix" },
    { name: "g!abraco", desc: "📝 [🤗] Dê um abraço em alguém (Alias).", category: "social", type: "prefix" },
    { name: "g!kiss", desc: "📝 [💋] Dê um beijo em alguém.", category: "social", type: "prefix" },
    { name: "g!beijo", desc: "📝 [💋] Dê um beijo em alguém (Alias).", category: "social", type: "prefix" },
    { name: "g!marriage", desc: "📝 [💍] Comandos de casamento e família.", category: "social", type: "prefix" },
    { name: "g!social_actions", desc: "📝 [🎭] Comandos de interação social (GIFs).", category: "social", type: "prefix" },
    { name: "g!social_profile", desc: "📝 [👤] Perfil social e reputação.", category: "social", type: "prefix" },

    // Utilidade
    { name: "g!calc", desc: "📝 [🧮] Calcula uma expressão matemática.", category: "utils", type: "prefix" },
    { name: "g!math", desc: "📝 [🧮] Calcula uma expressão matemática (Alias).", category: "utils", type: "prefix" },
    { name: "g!color", desc: "📝 [🎨] Mostra uma cor baseada no código HEX.", category: "utils", type: "prefix" },
    { name: "g!cor", desc: "📝 [🎨] Mostra uma cor baseada no código HEX (Alias).", category: "utils", type: "prefix" },
    { name: "g!decode", desc: "📝 [🔓] Decodifica texto de Base64.", category: "utils", type: "prefix" },
    { name: "g!education", desc: "📝 [🎓] Comandos de ciência e educação.", category: "utils", type: "prefix" },
    { name: "g!embed", desc: "📝 [📝] Cria um embed a partir de JSON.", category: "utils", type: "prefix" },
    { name: "g!emote", desc: "📝 [😃] Mostra um emoji em tamanho grande.", category: "utils", type: "prefix" },
    { name: "g!emoji", desc: "📝 [😃] Mostra um emoji em tamanho grande (Alias).", category: "utils", type: "prefix" },
    { name: "g!encode", desc: "📝 [🔒] Codifica texto em Base64.", category: "utils", type: "prefix" },
    { name: "g!github", desc: "📝 [🐙] Mostra informações de um usuário do GitHub.", category: "utils", type: "prefix" },
    { name: "g!gh", desc: "📝 [🐙] Mostra informações de um usuário do GitHub (Alias).", category: "utils", type: "prefix" },
    { name: "g!help", desc: "📝 [📚] Mostra a lista de todos os comandos disponíveis.", category: "utils", type: "prefix" },
    { name: "g!ajuda", desc: "📝 [📚] Mostra a lista de todos os comandos disponíveis (Alias).", category: "utils", type: "prefix" },
    { name: "g!ler", desc: "📝 [🗣️] Fala uma mensagem no canal de voz.", category: "utils", type: "prefix" },
    { name: "g!tts", desc: "📝 [🗣️] Fala uma mensagem no canal de voz (Alias).", category: "utils", type: "prefix" },
    { name: "g!lerfoto", desc: "📝 [📷] Lê o texto de uma imagem enviada ou link.", category: "utils", type: "prefix" },
    { name: "g!ocr", desc: "📝 [📝] Extrai texto de uma imagem.", category: "utils", type: "prefix" },
    { name: "g!qrcode", desc: "📝 [📱] Gera um QR Code.", category: "utils", type: "prefix" },
    { name: "g!qr", desc: "📝 [📱] Gera um QR Code (Alias).", category: "utils", type: "prefix" },
    { name: "g!remindme", desc: "📝 [⏰] Define um lembrete.", category: "utils", type: "prefix" },
    { name: "g!lembrete", desc: "📝 [⏰] Define um lembrete (Alias).", category: "utils", type: "prefix" },
    { name: "g!reverse", desc: "📝 [🔄] Inverte o texto.", category: "utils", type: "prefix" },
    { name: "g!inverter", desc: "📝 [🔄] Inverte o texto (Alias).", category: "utils", type: "prefix" },
    { name: "g!shorten", desc: "📝 [🔗] Encurta uma URL.", category: "utils", type: "prefix" },
    { name: "g!encurtar", desc: "📝 [🔗] Encurta uma URL (Alias).", category: "utils", type: "prefix" },
    { name: "g!steam", desc: "📝 [🎮] Busca informações de um jogo na Steam.", category: "utils", type: "prefix" },
    { name: "g!jogo", desc: "📝 [🎮] Busca informações de um jogo na Steam (Alias).", category: "utils", type: "prefix" },
    { name: "g!translate", desc: "📝 [🌐] Traduz um texto.", category: "utils", type: "prefix" },
    { name: "g!traduzir", desc: "📝 [🌐] Traduz um texto (Alias).", category: "utils", type: "prefix" },
    { name: "g!tiktok_video.mp4", desc: "📝 [🎥] Baixa vídeo do TikTok sem marca d'água.", category: "utils", type: "prefix" },
    { name: "g!voice_tools", desc: "📝 [🔊] Ferramentas de voz (TTS e Soundboard).", category: "utils", type: "prefix" },
    { name: "g!vote", desc: "📝 [📊] Cria uma votação simples.", category: "utils", type: "prefix" },
    { name: "g!enquete", desc: "📝 [📊] Cria uma votação simples (Alias).", category: "utils", type: "prefix" },
    { name: "g!weather", desc: "📝 [🌦️] Mostra a previsão do tempo.", category: "utils", type: "prefix" },
    { name: "g!clima", desc: "📝 [🌦️] Mostra a previsão do tempo (Alias).", category: "utils", type: "prefix" },
    { name: "g!wiki", desc: "📝 [📖] Pesquisa na Wikipedia.", category: "utils", type: "prefix" },
    { name: "g!wikipedia", desc: "📝 [📖] Pesquisa na Wikipedia (Alias).", category: "utils", type: "prefix" },

    // Minecraft Extended
    { name: "g!mcskin", desc: "📝 [🧱] Mostra a skin completa do jogador (Embed).", category: "minecraft", type: "prefix" },
    { name: "g!mchead", desc: "📝 [🧱] Mostra apenas a cabeça do jogador (Ícone).", category: "minecraft", type: "prefix" },
    { name: "g!mcbody", desc: "📝 [🧱] Renderiza o corpo do jogador em 3D ou 2D.", category: "minecraft", type: "prefix" },
    { name: "g!mcuuid", desc: "📝 [🧱] Mostra UUID, histórico de nomes e se é original.", category: "minecraft", type: "prefix" },
    { name: "g!mcserver", desc: "📝 [🧱] Status, MOTD, ping e players de um servidor IP.", category: "minecraft", type: "prefix" },
    { name: "g!mcplayers", desc: "📝 [🧱] Lista nomes dos jogadores online (se disponível).", category: "minecraft", type: "prefix" },
    { name: "g!mcconquista", desc: "📝 [🧱] Gera imagem 'Conquista Desbloqueada' personalizada.", category: "minecraft", type: "prefix" },
    { name: "g!mccraft", desc: "📝 [🧱] Mostra a receita de crafting de um item.", category: "minecraft", type: "prefix" },
    { name: "g!mcblock", desc: "📝 [🧱] Exibe informações e resistência de um bloco.", category: "minecraft", type: "prefix" },

    // Social Extended
    { name: "g!marry", desc: "📝 [💍] Envia pedido de casamento (Salva data se aceito).", category: "social", type: "prefix" },
    { name: "g!divorce", desc: "📝 [💔] Termina o casamento atual (Pode ter taxas).", category: "social", type: "prefix" },
    { name: "g!ship", desc: "📝 [💘] Calcula compatibilidade amorosa com gifs animados.", category: "social", type: "prefix" },
    { name: "g!cuddle", desc: "📝 [🤗] Faz carinho/chamego (abraço deitado).", category: "social", type: "prefix" },
    { name: "g!pat", desc: "📝 [💆] Faz cafuné na cabeça de alguém.", category: "social", type: "prefix" },
    { name: "g!poke", desc: "📝 [👉] Cutuca alguém para chamar atenção.", category: "social", type: "prefix" },
    { name: "g!tickle", desc: "📝 [🤣] Faz cócegas em alguém.", category: "social", type: "prefix" },
    { name: "g!handhold", desc: "📝 [🤝] Segura a mão de alguém (fofo).", category: "social", type: "prefix" },
    { name: "g!avaliarhusbando", desc: "📝 [🤵] Avalia um personagem/usuário de 1 a 10.", category: "social", type: "prefix" },

    // Utils & Fun Extended
    { name: "g!anagrama", desc: "📝 [🔠] Cria anagrama e calcula permutações possíveis.", category: "fun", type: "prefix" },
];

// --- Global Initialization ---
document.addEventListener('DOMContentLoaded', () => {
    // 1. Mouse Tracking for Grid Effect
    document.addEventListener('mousemove', (e) => {
        const x = e.clientX;
        const y = e.clientY;
        document.body.style.setProperty('--mouse-x', `${x}px`);
        document.body.style.setProperty('--mouse-y', `${y}px`);
    });

    // 2. Init Commands Page if element exists
    if (document.getElementById('category-list')) {
        initCommandsPage();
    }

    // 3. Init Chatbox (Always)
    initChatbox();
});

function initCommandsPage() {
    const categoryList = document.getElementById('category-list');
    const commandsList = document.getElementById('commands-list');
    const searchInput = document.getElementById('cmd-search');
    const categoryTitle = document.getElementById('category-title');
    const categoryDesc = document.getElementById('category-desc');

    const categories = [
        { id: 'all', name: 'Todos', icon: 'fa-layer-group', desc: 'Visualizando todos os comandos disponíveis.' },
        { id: 'mod', name: 'Moderação', icon: 'fa-shield-halved', desc: 'Ferramentas essenciais para manter a ordem.' },
        { id: 'config', name: 'Configuração', icon: 'fa-gear', desc: 'Personalize o bot para seu servidor.' },
        { id: 'eco', name: 'Economia', icon: 'fa-coins', desc: 'Sistema financeiro e loja virtual.' },
        { id: 'rpg', name: 'RPG', icon: 'fa-dragon', desc: 'Aventuras, batalhas e companheiros.' },
        { id: 'pets', name: 'Pets', icon: 'fa-paw', desc: 'Sistema de pets e evolução.' },
        { id: 'music', name: 'Música', icon: 'fa-music', desc: 'DJ de alta qualidade para seu canal de voz.' },
        { id: 'utils', name: 'Utilitários', icon: 'fa-wand-magic-sparkles', desc: 'Ferramentas diversas e diversão.' },
        { id: 'discord', name: 'Discord', icon: 'fa-brands fa-discord', desc: 'Ferramentas nativas do Discord.' },
        { id: 'fun', name: 'Diversão', icon: 'fa-gamepad', desc: 'Minigames e interações divertidas.' },
        { id: 'img', name: 'Imagens', icon: 'fa-image', desc: 'Manipulação de imagens e memes.' },
        { id: 'shop', name: 'Loja', icon: 'fa-store', desc: 'Loja virtual e produtos.' },
        { id: 'minecraft', name: 'Minecraft', icon: 'fa-cube', desc: 'Ferramentas para Minecraft.' },
        { id: 'social', name: 'Social', icon: 'fa-heart', desc: 'Interações sociais e casamentos.' },
        { id: 'users', name: 'Usuários', icon: 'fa-user', desc: 'Informações de usuários e avatares.' },
        { id: 'admin', name: 'Admin', icon: 'fa-user-shield', desc: 'Comandos administrativos (Prefix).' }
    ];

    let currentCategory = 'all';

    function renderCategories() {
        if (!categoryList) return;
        categoryList.innerHTML = '';
        categories.forEach(cat => {
            const count = cat.id === 'all' ? commands.length : commands.filter(c => c.category === cat.id).length;

            const div = document.createElement('div');
            div.className = `cat-item ${currentCategory === cat.id ? 'active' : ''}`;
            div.onclick = () => selectCategory(cat.id);
            div.innerHTML = `
                <div style="display: flex; align-items: center; gap: 12px;">
                    <i class="fa-solid ${cat.icon}"></i>
                    <span>${cat.name}</span>
                </div>
                <span class="cat-count">${count}</span>
            `;
            categoryList.appendChild(div);
        });
    }

    function selectCategory(id) {
        currentCategory = id;
        const catInfo = categories.find(c => c.id === id);
        if (categoryTitle) categoryTitle.textContent = catInfo.name;
        if (categoryDesc) categoryDesc.textContent = catInfo.desc;
        renderCategories();
        renderCommands();
    }

    function renderCommands() {
        if (!commandsList) return;
        commandsList.innerHTML = '';
        const filter = searchInput ? searchInput.value.toLowerCase() : '';

        const filtered = commands.filter(cmd => {
            const catMatch = currentCategory === 'all' || cmd.category === currentCategory;
            const searchMatch = cmd.name.toLowerCase().includes(filter) || cmd.desc.toLowerCase().includes(filter);
            return catMatch && searchMatch;
        });

        if (filtered.length === 0) {
            commandsList.innerHTML = '<div style="grid-column: 1/-1; text-align: center; color: var(--text-secondary); padding: 40px;">Nenhum comando encontrado.</div>';
            return;
        }

        // Separate Slash and Prefix
        const slashCommands = filtered.filter(c => c.type === 'slash');
        const prefixCommands = filtered.filter(c => c.type === 'prefix');

        let globalIndex = 1;

        if (slashCommands.length > 0) {
            if (currentCategory === 'all') {
                const header = document.createElement('div');
                header.className = 'cmd-section-header';
                header.innerHTML = `
                    <div class="cmd-section-icon"><i class="fa-solid fa-slash"></i></div>
                    <div class="cmd-section-info">
                        <h3>Slash Commands</h3>
                        <p>Comandos modernos nativos do Discord</p>
                    </div>
                `;
                commandsList.appendChild(header);
            }

            slashCommands.forEach(cmd => {
                createCommandCard(cmd, globalIndex++);
            });
        }

        if (prefixCommands.length > 0) {
            if (currentCategory === 'all') {
                const header = document.createElement('div');
                header.className = 'cmd-section-header';
                header.innerHTML = `
                    <div class="cmd-section-icon"><i class="fa-solid fa-terminal"></i></div>
                    <div class="cmd-section-info">
                        <h3>Prefix Commands (g!)</h3>
                        <p>Comandos clássicos usando o prefixo g!</p>
                    </div>
                `;
                commandsList.appendChild(header);
            }

            prefixCommands.forEach(cmd => {
                createCommandCard(cmd, globalIndex++);
            });
        }
    }

    function createCommandCard(cmd, index) {
        const div = document.createElement('div');
        div.className = 'command-card';
        // Add copy capability
        div.onclick = (e) => {
            // Prevent triggering if selecting text
            if (window.getSelection().toString().length === 0) {
                copyToClipboard(cmd.name);
                showToast(`Comando copiado: ${cmd.name}`);
            }
        };

        div.innerHTML = `
            <div class="cmd-card-header">
                <div style="display: flex; align-items: center; gap: 10px;">
                    <span class="cmd-number">#${index}</span>
                    <span class="cmd-name">${cmd.name}</span>
                </div>
                <span class="cmd-tag">${getCategoryName(cmd.category)}</span>
            </div>
            <p class="cmd-desc">${cmd.desc}</p>
            <div class="cmd-card-footer">
                <i class="fa-regular fa-copy"></i>
                <span>Clique para copiar</span>
            </div>
        `;
        commandsList.appendChild(div);
    }

    function copyToClipboard(text) {
        navigator.clipboard.writeText(text).catch(err => {
            console.error('Could not copy text: ', err);
        });
    }

    function showToast(message) {
        const toast = document.createElement('div');
        toast.className = 'toast-notification';
        toast.innerHTML = `<i class="fa-solid fa-check"></i> ${message}`;
        document.body.appendChild(toast);

        // Trigger reflow
        toast.offsetHeight;

        toast.classList.add('show');

        setTimeout(() => {
            toast.classList.remove('show');
            setTimeout(() => {
                toast.remove();
            }, 300);
        }, 3000);
    }

    function getCategoryName(id) {
        const cat = categories.find(c => c.id === id);
        return cat ? cat.name : id;
    }

    if (searchInput) {
        searchInput.addEventListener('input', renderCommands);
    }

    // Initial Render
    renderCategories();
    renderCommands();
}

// --- Chatbox Logic ---
function initChatbox() {
    // 1. Ensure Widget Exists
    let widget = document.getElementById('chatbox-widget');

    // If widget container doesn't exist (or is empty), create/fill it
    if (!widget || widget.innerHTML.trim() === '') {
        if (!widget) {
            widget = document.createElement('div');
            widget.className = 'chatbox-widget';
            widget.id = 'chatbox-widget';
            document.body.appendChild(widget);
        }

        widget.innerHTML = `
            <div class="chat-toggle" id="chat-toggle">
                <i class="fa-solid fa-comments"></i>
            </div>
            <div class="chat-window" id="chat-window">
                <div class="chat-header">
                    <span style="font-weight: 600; display: flex; align-items: center; gap: 12px;">
                        <img src="assets/images/logo.jpg" style="width: 32px; height: 32px; border-radius: 50%; border: 2px solid rgba(255,255,255,0.1);">
                        <div>
                            <div style="line-height: 1;">Ghost Assistant</div>
                            <div style="font-size: 0.75rem; color: #22c55e; margin-top: 4px;">● Online</div>
                        </div>
                    </span>
                    <i class="fa-solid fa-xmark" id="chat-close" style="cursor: pointer; color: var(--text-secondary); font-size: 1.2rem;"></i>
                </div>
                <div class="chat-body" id="chat-body">
                    <div class="msg bot">
                        Olá! Sou o assistente virtual do Ghost. Como posso ajudar você hoje?
                    </div>
                    <div class="chat-options" id="chat-options">
                        <button class="chat-btn" data-type="commands">📜 Quais os comandos?</button>
                        <button class="chat-btn" data-type="add">🤖 Como adicionar o bot?</button>
                        <button class="chat-btn" data-type="support">🆘 Preciso de suporte humano</button>
                        <button class="chat-btn" data-type="features">✨ O que o bot faz?</button>
                    </div>
                </div>
            </div>
        `;
    }

    const toggle = document.getElementById('chat-toggle');
    const windowEl = document.getElementById('chat-window');
    const close = document.getElementById('chat-close');
    const body = document.getElementById('chat-body');

    // Toggle Logic
    toggle.onclick = () => {
        const isFlex = windowEl.style.display === 'flex';
        windowEl.style.display = isFlex ? 'none' : 'flex';
    };

    close.onclick = () => {
        windowEl.style.display = 'none';
    };

    // Button Logic (Event Delegation)
    const optionsContainer = document.getElementById('chat-options');
    optionsContainer.onclick = (e) => {
        if (e.target.classList.contains('chat-btn')) {
            const type = e.target.getAttribute('data-type');
            handleChatInteraction(type);
        }
    };

    function handleChatInteraction(type) {
        let userText = "";
        let botResponse = "";

        switch (type) {
            case 'commands':
                userText = "Quais os comandos?";
                botResponse = "Você pode ver a lista completa na nossa página de <a href='commands.html' style='color: #ff0000; font-weight: bold;'>Comandos</a>. Lá tem tudo detalhado!";
                break;
            case 'add':
                userText = "Como adicionar o bot?";
                botResponse = "É fácil! Clique no botão 'Adicionar' no topo do site ou <a href='https://discord.com/oauth2/authorize?client_id=1439278544164487328&permissions=8&integration_type=0&scope=bot' target='_blank' style='color: #ff0000; font-weight: bold;'>clique aqui</a> para convidar agora mesmo.";
                break;
            case 'support':
                userText = "Preciso de suporte humano";
                botResponse = "Sem problemas! Entre no nosso <a href='https://discord.gg/w982KFEUps' target='_blank' style='color: #ff0000; font-weight: bold;'>Servidor do Discord</a> e abra um ticket na área de suporte.";
                break;
            case 'features':
                userText = "O que o bot faz?";
                botResponse = "O Ghost é completo! Moderação automática, economia, loja virtual, tickets, música, RPG e muito mais. Tudo em um só bot.";
                break;
        }

        addMessage(userText, 'user');

        // Show typing indicator
        const typing = document.createElement('div');
        typing.className = 'msg bot';
        typing.innerHTML = '<i class="fa-solid fa-ellipsis fa-fade"></i>';
        body.insertBefore(typing, optionsContainer);
        body.scrollTop = body.scrollHeight;

        setTimeout(() => {
            typing.remove();
            addMessage(botResponse, 'bot');
        }, 800);
    }

    function addMessage(html, sender) {
        const div = document.createElement('div');
        div.className = `msg ${sender}`;
        div.innerHTML = html;
        body.insertBefore(div, optionsContainer);
        body.scrollTop = body.scrollHeight;
    }
}

// --- Payment System Logic (Pushin Pay Integration) ---
const PUSHIN_PAY_TOKEN = "54542|bhvOG7jMs19LKRi1qR7BEhfSF5e06f8tvQcgbDkp76ac3bc2";
let paymentCheckInterval = null;

async function initiatePurchase(amountSonhos, priceCents) {
    const modal = document.getElementById('payment-modal');
    if (!modal) return;

    // 1. Show Modal & Reset State
    modal.style.display = 'flex';
    document.getElementById('pix-qr-code').style.display = 'none';
    document.getElementById('qr-loading').style.display = 'flex';
    document.getElementById('pix-copypaste').value = '';

    // Stop any previous checking interval
    if (paymentCheckInterval) clearInterval(paymentCheckInterval);

    try {
        // 2. Call Pushin Pay API to create Pix
        const paymentData = await createPushinPayPix(amountSonhos, priceCents);

        if (paymentData) {
            // 3. Update Modal with Real Data
            document.getElementById('qr-loading').style.display = 'none';

            const qrImg = document.getElementById('pix-qr-code');
            // Assuming API returns a base64 image or we generate one from the copy-paste code
            // If Pushin Pay returns a direct QR image URL, usage is direct. 
            // If they return just payload, we use a generator.
            // Based on standard behavior, we'll try to use the payload to generate the QR.
            if (paymentData.qr_code_base64) {
                qrImg.src = `data:image/png;base64,${paymentData.qr_code_base64}`;
            } else if (paymentData.qr_code_payload) {
                qrImg.src = `https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=${encodeURIComponent(paymentData.qr_code_payload)}`;
            }

            qrImg.style.display = 'block';

            // Set Copy Paste
            document.getElementById('pix-copypaste').value = paymentData.qr_code_payload;

            // 4. Start Checking for Payment Status
            startPaymentCheck(paymentData.id);
        } else {
            alert("Erro ao criar pagamento. Tente novamente.");
            closePaymentModal();
        }

    } catch (error) {
        console.error("Payment Error:", error);
        alert("Erro ao conectar com o gateway de pagamento.");
        closePaymentModal();
    }
}

async function createPushinPayPix(amountSonhos, priceCents) {
    const url = 'https://api.pushinpay.com.br/api/pix/cashIn';
    const body = {
        value: priceCents, // Value in cents
        webhook_url: "https://seusite.com/webhook", // Optional or placeholder
        external_reference: `GHOST_${Date.now()}_${amountSonhos}`,
        description: `Compra de ${amountSonhos} Sonhos - Ghost Bot`
    };

    try {
        const response = await fetch(url, {
            method: 'POST',
            headers: {
                'Content-Type': 'application/json',
                'Authorization': `Bearer ${PUSHIN_PAY_TOKEN}`,
                'Accept': 'application/json'
            },
            body: JSON.stringify(body)
        });

        const data = await response.json();

        // Adjust based on actual API response structure
        // Assuming data structure based on common providers: { id: "...", qr_code: "...", qr_code_base64: "..." }
        // If the structure is different, this part will need debugging with the real response.
        if (response.ok) {
            return data;
        } else {
            console.error("API Response Error:", data);
            return null;
        }
    } catch (err) {
        console.error("Fetch Error:", err);
        return null;
    }
}

function startPaymentCheck(transactionId) {
    if (paymentCheckInterval) clearInterval(paymentCheckInterval);

    let checks = 0;
    const maxChecks = 60; // 5 minutes (5s interval)

    paymentCheckInterval = setInterval(async () => {
        checks++;
        if (checks > maxChecks) {
            clearInterval(paymentCheckInterval);
            return;
        }

        const status = await checkPaymentStatus(transactionId);

        if (status === 'paid' || status === 'approved' || status === 'concluded') {
            clearInterval(paymentCheckInterval);
            alert("Pagamento Aprovado! Seus Sonhos foram creditados (Simulação).");
            closePaymentModal();
        }
    }, 5000);
}

async function checkPaymentStatus(transactionId) {
    // This endpoint might vary. 'cashIn/{id}' or similar is standard.
    // Assuming GET /api/pix/cashIn/{transactionId}/status or just /{transactionId}
    const url = `https://api.pushinpay.com.br/api/pix/cashIn/${transactionId}`;

    try {
        const response = await fetch(url, {
            method: 'GET',
            headers: {
                'Authorization': `Bearer ${PUSHIN_PAY_TOKEN}`,
                'Accept': 'application/json'
            }
        });

        const data = await response.json();
        if (response.ok) {
            return data.status; // 'pending', 'paid', etc.
        }
    } catch (err) {
        console.error("Status Check Error:", err);
    }
    return 'pending';
}

function closePaymentModal() {
    const modal = document.getElementById('payment-modal');
    if (modal) {
        modal.style.display = 'none';
    }
    if (paymentCheckInterval) clearInterval(paymentCheckInterval);
}

function copyPixCode() {
    const input = document.getElementById('pix-copypaste');
    input.select();
    input.setSelectionRange(0, 99999); // Mobile

    navigator.clipboard.writeText(input.value).then(() => {
        // Show a temporary feedback
        const btn = document.querySelector('.btn-icon');
        const original = btn.innerHTML;
        btn.innerHTML = '<i class="fa-solid fa-check"></i>';
        setTimeout(() => {
            btn.innerHTML = original;
        }, 2000);
    });
}

// Close modal if clicking outside
window.onclick = function (event) {
    const modal = document.getElementById('payment-modal');
    if (event.target == modal) {
        closePaymentModal();
    }
}
