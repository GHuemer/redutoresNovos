# Landing Page — Venda de Redutores Industriais (Projeto Original)

## Categoria
**Landing Page / Conversão Comercial**

## Detalhes
Página voltada à **geração de oportunidades comerciais** para a venda de redutores industriais novos da **REDUMEC**.  
O objetivo é apresentar os diferenciais técnicos, customizações disponíveis e incentivar o contato direto via **WhatsApp** ou formulário modal.  
O layout é **responsivo**, **institucional** e otimizado para **conversão mobile**.

## Objetivo Principal
Gerar **leads qualificados** e pedidos de orçamento para redutores novos, destacando:
- Alta performance dos modelos  
- Opções de customização  
- Rapidez no atendimento técnico e comercial

## Foco
- Destacar desempenho e durabilidade dos redutores  
- Oferecer fácil acesso ao time técnico e de vendas  
- Reforçar confiança da REDUMEC como referência em soluções sob medida  
- Garantir experiência fluida, independente do dispositivo de acesso

## Tecnologias (Frontend)
- **HTML5** — Estrutura semântica otimizada para SEO e acessibilidade  
- **CSS3** — Estilo responsivo, uso de variáveis institucionais (cores, espaçamento, tipografia)  
- **JavaScript (vanilla)** — Controle do modal, submissão do formulário para WhatsApp via `encodeURIComponent`,  
  animações suaves (Intersection Observer) e bloqueio de scroll quando o modal está ativo

## Design & UX
- Layout **profissional e técnico**, com hierarquia visual clara (título → benefícios → CTA)  
- **CTA dominante** no hero section e botão flutuante do WhatsApp  
- **Modal de orçamento** como alternativa para leads que preferem deixar dados antes do contato direto  
- **Blocos de benefícios** e diferenciais apresentados com ícones e frases curtas  
- **Depoimentos e cases de sucesso** reforçando credibilidade e resultados  
- **Acessibilidade**: uso de `aria-labels`, contraste adequado e foco visível em inputs  
- **Mobile-first**: imagens otimizadas, botões full-width e espaçamento de toque confortável

## Otimização
- Meta tags completas (`description`, `theme-color`, `viewport`) e favicon institucional  
- Imagens otimizadas (preferência por **WebP**) e `loading="lazy"` em elementos não críticos  
- CSS modularizado e minificado, evitando dependências externas  
- Links de WhatsApp construídos com `encodeURIComponent` para evitar erros de encoding  
- Cache e compressão ativados para melhor desempenho  
- Análise de SEO com foco em palavras-chave:  
  *redutores industriais, redutores customizados, manutenção e venda de redutores*

## Estratégia de Deploy
- **Amazon S3** — Hospedagem estática segura e performática  
- **Amazon CloudFront** — CDN global com compressão e cache geodistribuído  
- **AWS Certificate Manager (ACM)** — Certificado SSL/TLS gratuito e automático  
- **DNS** — Configuração de domínio com CNAME/ALIAS apontando para o CloudFront  
- **Monitoramento** — Logs de acesso ativados e integração com **CloudWatch** para métricas de tráfego e erros

## Extras
- Integração com **Google Analytics 4** e **Meta Pixel** para rastreamento de conversões  
- **Testes A/B** simples em texto e cor dos botões de CTA  
- Script automático no WhatsApp com mensagem de boas-vindas e coleta inicial de informações  
- Possibilidade de integração futura com **CRM (HubSpot / RD Station)** para acompanhamento de leads
