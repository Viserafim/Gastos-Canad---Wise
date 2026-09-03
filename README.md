# Controle de Gastos CAD — V2.3

PWA para duas pessoas, com funcionamento offline.

- IndexedDB
- Entradas e despesas
- Despesas individuais e compartilhadas
- Divisão 50/50 ou personalizada
- Editar/excluir
- Resumo por pessoa
- Sem cálculo de dívida/acerto entre as pessoas
- Backup/restauração
- Service Worker offline


V2.2: despesas compartilhadas descontam automaticamente a parcela de cada pessoa do saldo individual (50/50 ou divisão personalizada), mantendo o cálculo de acerto separado.


V2.3: despesas compartilhadas descontam diretamente do saldo de cada pessoa conforme a divisão; não há cálculo de acerto/dívida entre as pessoas. Os nomes salvos em Pessoas e saldos iniciais são usados automaticamente nos campos de quem pagou/recebeu e na divisão personalizada.
