# Política de segurança

A segurança do JADÁ e a privacidade de quem usa o app são prioridade. Obrigado por ajudar a manter o projeto seguro.

## Como reportar uma vulnerabilidade

**Não abra uma issue pública** para relatar falhas de segurança.

Use o canal privado do GitHub:

1. Vá até a aba **Security** deste repositório.
2. Clique em **Report a vulnerability** (relato privado de vulnerabilidade).
3. Descreva o problema com o máximo de detalhes possível.

Se esse botão não estiver disponível, abra uma issue **sem detalhes técnicos** pedindo um contato privado, e o mantenedor ([@paulohenz](https://github.com/paulohenz)) vai responder com um canal seguro.

## O que incluir

- Tipo de problema (ex.: injeção, contorno dos limites de envio, exposição de dados, XSS).
- Página, endpoint ou fluxo afetado.
- Passo a passo para reproduzir e, se possível, uma prova de conceito.
- Impacto estimado (o que alguém mal-intencionado conseguiria fazer).

## Escopo

Estão no escopo:
- o aplicativo JADÁ (front-end e API), inclusive formas de **manipular os relatos de fila em massa**, contornar os limites por aparelho/IP ou o sistema de denúncias;
- qualquer exposição de dados de usuários (IDs de aparelho, IPs).

Fora do escopo:
- os dados abertos do TSE em si (reporte direto à Justiça Eleitoral);
- ataques de negação de serviço volumétricos, engenharia social e spam.

## Nosso compromisso

- Confirmar o recebimento em até **5 dias úteis**.
- Manter você informado sobre a análise e a correção.
- Dar crédito pela descoberta, se você quiser, depois que a correção for publicada.

Pedimos que você não divulgue a falha publicamente antes da correção e que não acesse, altere ou apague dados de outras pessoas durante os testes.
