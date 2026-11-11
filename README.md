# simulado-pratico_sistemas-distribuidos

Nome: Elias Pina de Faria
RA: d3394422fb7587039be4

## O que fiz
analisei o código python já desenvolvido de uma empresa e realizei algumas correções.

##questões respondidas

Questão 1. O semáforo serve para limitar a quantidade de pedidos processados ao mesmo tempo, evitando excesso de acessos simultâneos.

Questão 2. Para manter a réplica atualizada com os dados do servidor principal e evitar informações desatualizadas.

Questão 3. É a capacidade do sistema de continuar funcionando mesmo quando ocorre uma falha. No programa, isso acontece quando o servidor principal fica offline e a réplica assume as consultas.

Questão 4. O Lock serve para impedir que várias threads alterem o estoque ao mesmo tempo, evitando erros e conflitos nos dados.

Questão 5. A sincronização deve acontecer depois do processamento dos pedidos, porque primeiro o estoque do servidor principal é atualizado e depois esse valor é copiado para a réplica.
