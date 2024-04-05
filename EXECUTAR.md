# Como Executar o OpenRadioss ?

O OpenRadioss é uma ferramenta de simulação composta por diferentes partes que trabalham juntas. Vamos entender cada parte:

1. **Starter**: Antes de começar a simulação, o Starter verifica se o modelo de entrada está correto e divide a malha em partes menores para processar mais rapidamente.

2. **Engine**: Essa é a parte principal que realmente executa a simulação. O Engine roda em paralelo, aproveitando múltiplos núcleos de processamento para terminar a simulação mais rápido.

3. **Bibliotecas**: O OpenRadioss usa algumas bibliotecas externas para funcionar corretamente. Você pode encontrar essas bibliotecas [aqui](https://github.com/AugustoCesarLacerda/REBRASIM-OpenRadioss/tree/main/extlib).

4. **Arquivos de Configuração**: Antes de rodar, você precisa configurar a simulação fornecendo alguns [arquivos de configuração](https://github.com/AugustoCesarLacerda/REBRASIM-OpenRadioss/tree/main/hm_cfg_files). Esses arquivos descrevem os dados de entrada para a simulação.

Para executar o OpenRadioss, siga estes passos:

1. Prepare o seu modelo e os arquivos de entrada.
2. Execute o Starter para verificar e dividir a malha.
3. Execute o Engine, passando os arquivos de configuração.
4. Aguarde enquanto a simulação paralela é executada.

Em suma, o Starter prepara o modelo, o Engine faz os cálculos pesados paralelamente, e você fornece as bibliotecas e arquivos de configuração necessários. É um processo integrado para realizar simulações complexas de forma eficiente.
