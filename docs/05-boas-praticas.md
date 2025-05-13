# Boas Práticas

## Nomeação

- Use padrões como `cliente-projeto-ambiente` para nomear recursos

## Segurança

- Evite deixar o IP "0.0.0.0/0" liberado em ambientes reais
- Use autenticação com Azure AD sempre que possível

## Backup

- Azure realiza backups automáticos (retém por 7 dias no plano básico)
- Para maior controle, configure backups adicionais

## Custo

- Monitore o uso com Azure Cost Management
- Use alertas de orçamento para evitar surpresas

## Limpeza

- Delete recursos não utilizados para evitar cobrança
