# Glossário proposto para CK3 — português brasileiro

**Estado:** rascunho para validação humana. As propostas da tabela foram aplicadas como primeira leva em `localization/replace/spanish/rc3_core_terms_l_spanish.yml`; as decisões indicadas abaixo continuam provisórias.

**Base:** Crusader Kings III 1.20.0.3. O inglês oficial orienta o sentido; o espanhol oficial orienta a mecânica e o espaço da interface que a tradução ocupará (`l_spanish`). A tradução italiana do Workshop serve apenas como referência adicional. As chaves abaixo foram conferidas nos arquivos de localização instalados, sobretudo `game_concepts`, `enum/land_tier` e `culture/culture_titles`.

**Critério de tamanho:** preferir rótulos próximos do espanhol em comprimento e número de palavras. Evitar abreviações pouco claras. Comprimento em caracteres é só uma triagem: fontes, acentos e contexto também afetam o encaixe. As propostas mais longas estão assinaladas nas decisões pendentes.

**Capitalização de títulos:** em termos curtos e emblemáticos, usar iniciais maiúsculas nas palavras principais, preservando artigos, preposições e conectivos em minúsculas; por exemplo, *Pequeno Rei* e *Alto Príncipe*.

**Títulos genéricos de clãs e tribos:** `Headman/Headwoman` → *Líder*; `Chieftain/Chieftess` → *Chefe*; `High Chief/High Chieftess` → *Alto Chefe/Alta Chefe*; `Chiefdom` → *Chefatura*. *Chefe* e *líder* são nomes de dois gêneros; os artigos e demais concordâncias dependem da frase. Reservar *cacique* para contextos culturais específicos, pois o termo designa originalmente chefes indígenas das Américas.

**Títulos mercenários padrão:** `Constable` → *Condestável*; `Host` → *Hoste*; `Captain` → *Capitão/Capitã*; `General` → *General*. *Tenente*, *Condestável* e *General* mantêm a mesma forma nas chaves masculina e feminina; as frases ao redor exigem concordância própria.

**Ordens militares padrão:** `Master/Mistress` → *Mestre/Mestra*; `Grandmaster/Grandmistress` → *Grão-Mestre/Grã-Mestra*; `Abbot General/Abbess General` → *Abade Geral/Abadessa Geral*. Os termos culturais próprios das ordens terão revisão separada.

## Território, títulos e hierarquia

| Chave | Inglês oficial | Espanhol oficial | PT-BR proposto |
| --- | --- | --- | --- |
| `barony` | Barony | Baronía | Baronia |
| `county` | County | Condado | Condado |
| `duchy` | Duchy | Ducado | Ducado |
| `kingdom` | Kingdom | Reino | Reino |
| `empire` | Empire | Imperio | Império |
| `hegemony` | Hegemony | Hegemonía | Hegemonia |
| `unlanded` | Unlanded | Sin tierra | Sem Terras |
| `baron` / `baron_female` | Baron / Baroness | Barón / Baronesa | Barão / Baronesa |
| `count` / `count_female` | Count / Countess | Conde / Condesa | Conde / Condessa |
| `duke` / `duke_female` | Duke / Duchess | Duque / Duquesa | Duque / Duquesa |
| `king` / `king_female` | King / Queen | Rey / Reina | Rei / Rainha |
| `emperor` / `emperor_female` | Emperor / Empress | Emperador / Emperatriz | Imperador / Imperatriz |
| `game_concept_title` | Title | Título | Título |
| `game_concept_primary_title` | Primary Title | Título principal | Título Principal |
| `game_concept_holder` | Holder | Titular | Titular |
| `game_concept_realm` | Realm | Señorío | Senhorio |
| `game_concept_domain` | Domain | Dominio | Domínio |
| `game_concept_domain_limit` | Domain Limit | Límite de dominio | Limite de domínio |
| `game_concept_holding` | Holding | Posesión | Possessão |
| `game_concept_de_jure` | De Jure | De iure | De Jure |
| `game_concept_de_jure_drift` | De Jure Drift | Deriva de iure | Integração de Jure |

## Poder e relações feudais

| Chave | Inglês oficial | Espanhol oficial | PT-BR proposto |
| --- | --- | --- | --- |
| `game_concept_ruler` | Ruler | Gobernante | Governante |
| `game_concept_vassal` | Vassal | Vasallo | Vassalo |
| `game_concept_vassalage` | Vassalage | Vasallaje | Vassalagem |
| `game_concept_direct_vassal` | Direct Vassal | Vasallo directo | Vassalo Direto |
| `game_concept_liege` | Liege | Señor | Senhor |
| `game_concept_rightful_liege` | Rightful Liege | Señor legítimo | Senhor Legítimo |
| `game_concept_vassal_contract` | Vassal Contract | Pacto de vasallaje | Pacto de Vassalagem |
| `game_concept_obligations` | Obligations | Obligaciones | Obrigações |
| `game_concept_tax` / `game_concept_taxes` | Tax / Taxes | Impuesto / Impuestos | Imposto / Impostos |
| `game_concept_crown_authority` | Crown Authority | Autoridad de la corona | Autoridade da Coroa |
| `game_concept_government` | Government | Gobierno | Governo |
| `game_concept_feudal` | Feudal | Feudal | Feudal |
| `game_concept_clan` | Clan | Clan | Clã |
| `game_concept_tribal` | Tribal | Tribal | Tribal |
| `game_concept_republic` | Republic | República | República |
| `game_concept_theocracy` | Theocracy | Teocracia | Teocracia |
| `game_concept_control` | Control | Control | Controle |
| `game_concept_development` | Development | Desarrollo | Desenvolvimento |
| `game_concept_opinion` | Opinion | Opinión | Opinião |
| `game_concept_tyranny` | Tyranny | Tiranía | Tirania |

## Direitos, guerra e diplomacia

| Chave | Inglês oficial | Espanhol oficial | PT-BR proposto |
| --- | --- | --- | --- |
| `game_concept_claim` | Claim | Derecho | Direito |
| `game_concept_pressed_claim` | Pressed Claim | Derecho reivindicado | Direito Firmado |
| `game_concept_unpressed_claim` | Unpressed Claim | Derecho no reivindicado | Direito Contestável |
| `game_concept_casus_belli` | Casus Belli | Casus belli | Casus Belli |
| `game_concept_war` | War | Guerra | Guerra |
| `game_concept_holy_war` | Holy War | Guerra Santa | Guerra Santa |
| `game_concept_crusade` | Crusade | Cruzada | Cruzada |
| `game_concept_war_score` | War Score | Puntuación bélica | Pontuação Bélica |
| `game_concept_siege` | Siege | Asedio | Cerco |
| `game_concept_army` | Army | Ejército | Exército |
| `game_concept_levy` / `game_concept_levies` | Levy / Levies | Leva / Levas | Leva / Levas |
| `game_concept_men_at_arms` | Men-at-Arms | Hombres de armas | Homens de Armas |
| `game_concept_knight` | Knight | Caballero | Cavaleiro |
| `game_concept_commander` | Commander | Comandante | Comandante |
| `game_concept_alliance` | Alliance | Alianza | Aliança |
| `game_concept_truce` | Truce | Tregua | Trégua |
| `game_concept_faction` | Faction | Facción | Facção |

## Dinastia, fé e personagens

| Chave | Inglês oficial | Espanhol oficial | PT-BR proposto |
| --- | --- | --- | --- |
| `game_concept_succession` | Succession | Sucesión | Sucessão |
| `game_concept_dynasty` | Dynasty | Dinastía | Dinastia |
| `game_concept_house` | House | Casa | Casa |
| `game_concept_cadet_branch` | Cadet Branch | Rama cadete | Ramo Cadete |
| `game_concept_prestige` | Prestige | Prestigio | Prestígio |
| `game_concept_dynasty_prestige` | Renown | Renombre | Renome |
| `game_concept_piety` | Piety | Piedad | Piedade |
| `game_concept_legitimacy` | Legitimacy | Legitimidad | Legitimidade |
| `game_concept_dread` | Dread | Temor | Temor |
| `game_concept_stress` | Stress | Estrés | Estresse |
| `game_concept_faith` | Faith | Fe | Fé |
| `game_concept_religion` | Religion | Religión | Religião |
| `game_concept_culture` | Culture | Cultura | Cultura |
| `game_concept_pilgrimage` | Pilgrimage | Peregrinación | Peregrinação |
| `game_concept_marriage` | Marriage | Matrimonio | Casamento |
| `game_concept_betrothal` | Betrothal | Compromiso | Noivado |
| `game_concept_court` | Court | Corte | Corte |
| `game_concept_courtier` | Courtier | Cortesano | Cortesão |
| `game_concept_councillor` | Councillor | Consejero | Conselheiro |
| `game_concept_chancellor` | Chancellor | Canciller | Chanceler |
| `game_concept_steward` | Steward | Administrador | Senescal |
| `game_concept_marshal` | Marshal | Mariscal | Marechal |
| `game_concept_spymaster` | Spymaster | Jefe de espías | Mestre de Espiões |
| `game_concept_hook` | Hook | Anzuelo | Trunfo |
| `game_concept_strong_hook` | Strong Hook | Anzuelo fuerte | Trunfo Forte |
| `game_concept_secret` | Secret | Secreto | Segredo |
| `game_concept_scheme` | Scheme | Conjura | Trama |
| `game_concept_intrigue` | Intrigue | Intriga | Intriga |

## Flexões diretas acrescentadas à primeira leva

Estas formas acompanham termos já escolhidos acima e também foram aplicadas ao arquivo de localização.

| Chave | Inglês oficial | Espanhol oficial | PT-BR proposto |
| --- | --- | --- | --- |
| `barony_plural` | Baronies | Baronías | Baronias |
| `county_plural` | Counties | Condados | Condados |
| `duchy_plural` | Duchies | Ducados | Ducados |
| `kingdom_plural` | Kingdoms | Reinos | Reinos |
| `empire_plural` | Empires | Imperios | Impérios |
| `hegemony_plural` | Hegemonies | Hegemonías | Hegemonias |
| `unlanded_plural` | Unlanded | Sin tierras | Sem Terras |
| `baron_plural` | Barons | Barones | Barões |
| `count_plural` | Counts | Condes | Condes |
| `duke_plural` | Dukes | Duques | Duques |
| `king_plural` | Kings | Reyes | Reis |
| `emperor_plural` | Emperors | Emperadores | Imperadores |
| `game_concept_vassals` | Vassals | Vasallos | Vassalos |
| `game_concept_direct_vassals` | Direct Vassals | Vasallos directos | Vassalos Diretos |
| `game_concept_rulers` | Rulers | Gobernantes | Governantes |
| `game_concept_titles` | Titles | Títulos | Títulos |
| `game_concept_holders` | Holders | Titulares | Titulares |
| `game_concept_realms` | Realms | Señoríos | Senhorios |
| `game_concept_domains` | Domains | Dominios | Domínios |
| `game_concept_holdings` | Holdings | Posesiones | Possessões |
| `game_concept_claims` | Claims | Derechos | Direitos |
| `game_concept_faiths` | Faiths | Fes | Fés |
| `game_concept_religions` | Religions | Religiones | Religiões |
| `game_concept_cultures` | Cultures | Culturas | Culturas |
| `game_concept_dynasties` | Dynasties | Dinastías | Dinastias |
| `game_concept_houses` | Houses | Casas | Casas |
| `game_concept_schemes` | Schemes | Conjuras | Tramas |
| `game_concept_factions` | Factions | Facciones | Facções |
| `game_concept_armies` | Armies | Ejércitos | Exércitos |
| `game_concept_knights` | Knights | Caballeros | Cavaleiros |
| `game_concept_wars` | Wars | Guerras | Guerras |

## Decisões para validar antes de fixar o vocabulário

1. **Senhor / suserano:** usar *senhor* para `liege`. O jogo também emprega `suzerain` em relações de sujeição; reservar *suserano* para esse conceito evita fundir mecânicas distintas. Conferir todos os usos antes de traduzir os textos longos.
2. **Senhorio / domínio / possessão:** `realm` é o conjunto político sob um governante; `domain` são as terras que ele detém pessoalmente; `holding` é uma propriedade dentro do mapa. Os três nomes precisam permanecer distintos.
3. **Direito Firmado / Direito Contestável:** são as opções propostas para `pressed claim` e `unpressed claim`. A diferença mecânica envolve a transmissão por herança, então esses dois rótulos continuam provisórios e devem ser conferidos nos textos explicativos e em jogo.
4. **Senescal:** nome de ofício medieval para `steward`, mais curto que *administrador*. Confirmar se a função exibida no conselho soa natural no restante da interface. *Mordomo* é outra opção histórica, mas hoje sugere uma função doméstica.
5. **Desenvolvimento:** excede bastante o espanhol *desarrollo* em largura. O sentido do atributo recomenda mantê-lo; verificar as telas estreitas antes de buscar uma abreviação.
6. **De Jure / Integração de Jure:** manter o latinismo já reconhecível para jogadores de CK3. *Integração de Jure* é mais longa que *Deriva de iure* e deve ser conferida nas telas estreitas. Em frases, ajustar artigos e preposições sem alterar as chaves `[de_jure|E]`.
7. **Homens de armas, cavaleiro, clã:** termos gerais. Títulos e unidades próprios de culturas específicas exigem decisões contextuais; não devem ser convertidos automaticamente por substituição global.

## Regra editorial para a tradução futura

Este arquivo orienta escolhas de palavras; não autoriza trocar texto dentro de chaves ou comandos. Em arquivos `.yml`, preservar literalmente nomes de chave, `$variáveis$`, `[funções|E]`, ícones `@...!`, marcas `#...#!` e `\n`. Traduzir apenas o texto que o jogador vê, respeitando o contexto gramatical e o espaço real da interface.
