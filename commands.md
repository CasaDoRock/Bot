Commands:
=========

X especifica um número
argumentos entre ( ) são opcionais


Manager
-------

|Comando | Argumentos | Descrição |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X | Deixa o tempo limite de ausência |
|!clearchat | | Limpa o chat |
|!cycle | | Ativa ou desativa o ciclo de DJ |
|!cycletimer | X | Limite da fila para quando o ciclo está ativado |
|!refresh | | F5 na página de quem está hospedando o bot |
|!usercmdcd | X | Tempo de cooldown de comandos para usuários comuns |
|!usercommands | | Ativar ou desativar comandos para usuários comuns |
|!voteskip | (X) | Quanto não tem argumento especificado, responde com o limite de voteskip, quando X for especificado, o limite para voteskip é atualizado |

Bouncer+
--------

|Comando | Argumentos | Descrição |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | add usuário para a lista de espera |
|!afkremoval | | Ativar ou desativar o kick por afk |
|!autoskip | | Pula a música automaticamente quando acabar (use quando o bug dos círculos aparecerem) |
|!bouncer+ | | desativa bouncer+ |
|!deletechat | @user | deleta todo o chat de um certo usuário ***Temporariamente desativado devido a um bug (esperando correção)*** |
|!lock | | tranca a lista de espera |
|!lockdown | | tranca a sala: só membro da staff podem digitar |
|!maxlength | X | mudar o limite de tempo máximo, apenas quando timeguard estiver ativo |
|!move | @user (X) | move usuário para posição X na lista de espera, o padrão é 1 |
|!remove | @user | remove usuário da lista de espera |
|!roulette | | começa um sorteio |
|!songstats | | ativar ou desativar estatísticas da música |
|!unlock | | destrancar a lista de espera  |
|!welcome | | ativar ou desativar a mensagem de boas vindas |

Bouncer
-------

|Comando | Argumentos | Descrição |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | Mostra quantos usuários conversou no chat nos últimos X minutos. Se X não for especificado, 60 é o padrão |
|!afkreset | @user | reseta o tempo de ausência de um usuário |
|!afktime | @user | Mostra a quanto tempo o usuário está ausente |
|!autodisable | | ativar ou desativar autodisable |
|!ban | @user | bane usuário por 1 dia |
|!blacklist / !bl | blacklistname | adiciona música para a blacklist especificada(op ou nsfw) |
|!blinfo | | Consegue informação necessária para colocar música na blacklist |
|!cycleguard | | ativar ou desativar cycleguard |
|!dclookup / !dc | (@user) | fazer um dclookup para usuário |
|!eta | (@user) | mostra em tempo estimado quando o usuário vai tocar |
|!filter | | ativar ou desativar filtro de chat(no momento não aconselhado) |
|!jointime | @user | mostra quanto tempo o usuário está na sala |
|!kick | (X) | kick o usuário por X minutos, o padrão é 0.25 minutos (15 segundos) |
|!kill | | desligar o bot |
|!lockguard | | ativar ou desativar o lockguard |
|!lockskip | (reason) | pula a música e move o DJ na fila (a posição pode ser definida com !lockskippos) |
|!lockskippos | X | define a posição que o DJ irá quando for usado !lockskip |
|!motd | (X)/(message) | quando não tem argumento especificado, retorna com mensagem do dia, quando X for especificado, a mensagem aparece a cada X músicas, quando mensagem for dada, autera a mensagem do dia |
|!mute | @user (X) | mutar o usuário, por X minutos se X for especificado, caso contrário, será mutado por tempo inderteminado |
|!reload | | recarregar o bot |
|!sessionstats | | mostra status da seção atual |
|!skip | | pula a música atual |
|!status | | mostra o status do bot e algumas configurações |
|!timeguard | | ativa ou desativa o timeguard |
|!togglebl | | ativa ou desativa a blacklist |
|!togglemotd | | ativa ou desativa a motd |
|!togglevoteskip | | ativa ou desativa o voteskip |
|!unban | @user | desbanir usuário |
|!unmute | @user | desmutar usuário |

Resident DJ
-----------

|Comando | Argumentos | Descrição |
|:------:|:---------:|:--------------------------------------:|
|!link | | dá o link para a música atual



User
----

|Comando | Argumentos | Descrição |
|:------:|:---------:|:--------------------------------------:|
|!autowoot | | é linkado para o PlugCubed, o plugin recomendado para dar "legal" automaticamente |
|!commands | | manda o link para comandos |
|!emoji | | link para uma lista de emojis |
|!eta | | mostra uma estimativa para até quando você irá tocar |
|!fb | | link para página do facebook (se configurado) |
|!help | | link para uma imagem para ajudar novatos no plug |
|!join | | entrar no sorteio, se estiver ativado |
|!leave | | sai do sorteio se você entrou |
|!link | | quando o usuário for o DJ, manda um link da música atual |
|!op | | Link para a lista de músicas tocadas excessivamente(se configurado )|
|!ping | | pong! |
