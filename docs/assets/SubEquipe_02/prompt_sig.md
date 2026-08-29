# Prompt Utilizado — Elaboração do SIG (NFR Framework)

Pra montar o SIG do App Pet Foco, pedi pra seguir a notação formal do 
NFR Framework do Chung (2000), com softgoals em nuvem no formato 
Tipo[Tópico], operacionalizações de borda tracejada, links de 
contribuição (+/++/-/--), correlação tracejada pra trade-offs e "!" 
marcando os softgoals mais críticos. O contexto era o nosso produto: um 
app de cuidar de pet inspirado no Tamagotchi, mas corrigindo os 
problemas que achamos na engenharia reversa (notificação sem pausa, 
evolução aleatória, isolamento sem controle dos pais, falta de 
transparência) e somando isso a um sistema de Pomodoro, onde o tempo de 
foco do jogador vira XP pro pet evoluir e comprar itens na loja.

Pedi seis softgoals independentes (uma floresta, não uma árvore só, já 
que Usabilidade, Desempenho, Engajamento, Transparência, Disponibilidade 
e Consistência não têm relação de decomposição natural entre si), com 
Engajamento e Transparência marcados como prioritários. O Pomodoro com 
XP entrou com peso ++ por ser o coração da proposta, e é dali que sai a 
correlação negativa com um softgoal de Retenção do Negócio — mostrando 
que a gente escolheu priorizar bem-estar do usuário mesmo sabendo que 
isso pode custar retenção a curto prazo. Pedi tudo em preto e branco, 
sem cor fazendo parte da notação, com legenda, e mantendo rastreabilidade 
direta com os problemas já mapeados no Rich Picture. Referência: CHUNG, 
L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-Functional Requirements in 
Software Engineering. Boston: Springer, 2000.
