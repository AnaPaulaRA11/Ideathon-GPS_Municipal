# Ideathon
## Semana SEMATEC da FATEC (2026) - Projeto em Grupo - GPS Municipal

### SOBRE O PROJETO

O GPS Municipal tem como objeto ser um sistema de GPS centralizado na prefeitura de cada município, permitindo maior controle e personalização nas rotas dado as circunstâncias da cidade como alagamentos, acidentes, obras e serviços, transito lento, engarrafamento e afins.

### ORGANIZAÇÃO DO SISTEMA

O Sistema será separado entre **Client** e **Server**.

O **Server** terá como função:

 * Permitir que a prefeitura registre incidentes que possam interferir no fluxo de trânsito habitual.
 * Montar rotas para percorrer a cidade, levando em consideração todos os incidentes e alterações no trânsito cadastrados.
 * Emitir alertas aos **Client**s sobre novos incidentes registrados.

O **Client** terá como função:

 * Requisitar rotas.
 * Receber os alertas do **Server**.
 * Avaliar se novos incidentes afetam rotas já estabelecidas, oferecendo a opção de pedir para recalcular a rota.