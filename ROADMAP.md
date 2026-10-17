# Roadmap do JADÁ

Planejamento vivo: as prioridades mudam conforme o feedback da comunidade. Sugestões? [Abra uma issue](../../issues/new/choose).

Legenda: ✅ pronto · 🚧 em andamento · 🗓️ planejado · 💭 ideia

## ✅ MVP (pronto)
- ✅ Importação completa dos dados abertos do TSE 2026 (todas as UFs: ~95,7 mil locais e ~517 mil seções)
- ✅ Busca nacional por cidade, bairro, zona, seção ou nome do local (sem acento)
- ✅ Página do local com status por seção, pessoas aproximadas, espera estimada e confiabilidade
- ✅ Fluxo "Informar fila" em 3 passos, confirmação e denúncia de relatos
- ✅ Estimativa robusta: mediana ponderada pelo tempo, descarte de outliers, estado "Relatos divergentes" e teto por eleitores da seção
- ✅ Proteções: um relato por aparelho a cada 10 min (substitui o anterior), limites de requisição, uma confirmação por aparelho, ocultação após 3 denúncias
- ✅ Mapa do Brasil com níveis (país → estado → município), filtros por movimento, zoom e arraste
- ✅ "Minha seção" salva no aparelho, sempre destacada no mapa
- ✅ Modo demonstração automático quando a API está fora do ar

## 🚧 Agora: preparação para o lançamento
- ✅ Publicação com domínio próprio: no ar em [jadabrasil.com.br](https://jadabrasil.com.br/) (front, API e banco)
- 🚧 Testes com grupos de eleitores em diferentes cidades
- 🚧 Ajustes de layout no celular (mapa e listas)
- 🗓️ Página de status/transparência: quantos relatos, quantos locais ativos
- 🗓️ Revisão de acessibilidade (WCAG 2.1 AA): contraste, foco, leitor de tela

## 🗓️ Próximos
- 🗓️ **PWA**: instalar na tela inicial e funcionar com conexão ruim
- 🗓️ **Alertas** "me avise quando a espera cair abaixo de X min" (notificação push)
- 🗓️ "Perto de mim" usando o índice geoespacial (locais mais próximos com status)
- 🗓️ Correções de dados de locais enviadas pela comunidade, com moderação
- 🗓️ Previsão por horário a partir do histórico (melhor horário para ir)
- 🗓️ Moderação: painel para revisar denúncias e padrões suspeitos
- 🗓️ Compartilhar o status do local (link e imagem para redes sociais)

## 💭 Depois das eleições
- 💭 Outras verticais com o mesmo motor de filas: eventos e shows, serviços públicos, hospitais, parques
- 💭 API pública de dados agregados e anônimos para pesquisa e imprensa
- 💭 Versões em inglês e espanhol

## ❌ Fora do escopo (de propósito)
- Qualquer conteúdo político: candidatos, partidos, pesquisas, intenção de voto, propaganda
- Coleta de dados pessoais ou de informações sobre o voto
- Contas obrigatórias para usar o app
