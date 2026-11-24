BATISFERA // ABYSSAL

Pesca Abissal Contemplativa — Um jogo incremental (idle/incremental) minimalista de exploração batimétrica profunda, coleta autônoma e catalogação taxonômica em arquivo único.

Visão Geral

BATISFERA // ABYSSAL coloca você no comando de uma sonda autônoma de longo alcance operando em estratos oceânicos que vão da superfície (0 m) até a Singularidade Abissal (50.000 m).

Projetado com estética de terminal científico escuro, tipografia monoespaçada e ilustração vetorial procedural em <svg>, o jogo funciona de maneira 100% autônoma — inclusive calculando coletas acumuladas durante períodos offline com base em carimbo de tempo real (UTC).

Principais Recursos

1. Sonda & Captura Batimétrica (0 m – 50.000 m)

10 Estratos Oceânicos: Da Zona Epipelágica até a Singularidade Abissal, cada camada exige resistência estrutural de casco e comprimento de linha adequados.

Ilustração Vetorial Procedural: Cada espécime é desenhado dinamicamente via <svg> determinístico gerado a partir de sua semente taxonômica (hash FNV-1a + PRNG Mulberry32), variando proporções de corpo, nadadeiras, espinhos, olhos e iscas bioluminescentes.

Marcos de Catalogação por Zona: Descobrir 10%, 25%, 50% e 100% das espécies de uma profundidade desbloqueia multiplicadores permanentes de biomassa (+10%, +25%, +60% e +150%) naquela camada.

2. Bestiário Combinatório (256.000 Espécies)

Banco taxonômico gerado pela combinação de 10 zonas × 25 espécies base × 16 prefixos × 16 sufixos × 4 mutações (Forma Basal, Mutação Bioluminescente, Mutação Gigantismo e Mutação Polimórfica).

8 Graus de Raridade: Comum, Incomum, Raro, Abissal, Ancestral, Anômalo, Relíquia e Mitológico.

Filtros Avançados: Inspeção de espécies Catalogadas ou Não Catalogadas (exibidas como silhuetas de sonar [x0]), filtro por profundidade, raridade, mutação, busca textual e ordenação por ordem cronológica de descoberta (1ª → Última).

3. Engenharia & Curva de Dificuldade Estendida

5 Sistemas Aprimoráveis: Linha de Titânio, Casco de Pressão Hidrostática, Automação do Guincho Contínuo, Isca Biológica Sintética e Sonar de Ressonância Rara.

Escala exponencial severa calibrada para progressão contemplativa de longo prazo.

4. Prestígio, Doutrinas & Desafios de Expedição

Nova Expedição (Prestígio): Reinicia créditos e melhorias de engenharia para converter a biomassa acumulada em Dados Abissais permanentes (+10% de rendimento global por unidade), preservando todo o Bestiário.

Árvore de Pesquisa (Doutrinas da Sonda): Três ramos permanentes financiados com Dados Abissais:

Ramo I — Telemetria: Chance de re-rolar duplicatas em busca de espécies inéditas e sintonização de raridade.

Ramo II — Extração: Bônus global de biomassa e valorização de espécimes mutantes.

Ramo III — Estabilidade Estrutural: Profundidade inicial ampliada e redução do tempo de ciclo do guincho.

4 Protocolos de Desafio: Restrições opcionais ativáveis antes de iniciar uma nova expedição (como proibição de melhorias no guincho, trava de profundidade em 200 m, proibição de iscas ou limite de nível de casco/linha) que concedem bônus permanentes de Dados Abissais e raridade.

5. Persistência & Simulação Offline

Salvamento automático em localStorage a cada 15 segundos e ao fechar a aba.

Cálculo de progresso offline baseado no tempo decorrido desde a última sessão ativa.

Exportação e importação manual do progresso completo em string Base64.

Como Executar

O projeto não requer servidor, compilação ou instalação de pacotes:

Faça o download do arquivo index-v7.html (ou renomeie-o para index.html).

Abra o arquivo diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari) ou hospede-o gratuitamente via GitHub Pages.

Estrutura Técnica

.
├── index.html   # Aplicação completa (HTML5 + CSS3 + Vanilla JS + SVG Procedural)
└── README.md       # Documentação do repositório


Zero dependências externas: Sem frameworks, bibliotecas de ícones ou chamadas de rede.

Persistência: Chave batisfera_abyssal_save_v2 no localStorage.
