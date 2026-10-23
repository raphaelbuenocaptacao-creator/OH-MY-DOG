# OH MY DOG! 🌭

**Uma mordida. Uma surpresa.**

Protótipo PWA de cardápio e simulação de compras para o negócio OH MY DOG! de Campos do Jordão/SP.

## Disponibilização

O repositório usa site estático GitHub Pages, branch `main`, pasta `/ (root)`. Caso o Pages não esteja ativo, vá a Settings → Pages → Build and deployment → Deploy from a branch → main / root → Save.

URL esperada após ativação: https://raphaelbuenocaptacao-creator.github.io/OH-MY-DOG/

## O que funciona na demonstração

- Página inicial responsiva, cardápio com cinco produtos ilustrativos e filtros.
- Personalização de molho, extras e observações.
- Carrinho com quantidades e cálculo de subtotal.
- Simulação de pedido com dados digitados no aparelho (armazenamento local), histórico e painel ilustrativo.
- MyDog Club mostrando regras propostas e catálogo de recompensas, sem créditos ou resgates reais.
- Manifest e service worker para experiência instalável e cache básico.

**AVISO: Não é um sistema de pedidos em produção.** Nenhum pedido é enviado à cozinha, não há conta de usuário, processamento de pagamentos, rastreamento, cálculo de frete, painel privado ou banco de dados. Não utilizar para receber pedidos reais.

## Pendências para lançamento

1. Confirmar lanches, ingredientes, fotos próprias e preços reais; fotos externas são apenas ilustrativas.
2. Endereço, telefone/WhatsApp comercial, horários efetivos e áreas/taxas de entrega.
3. Backend com banco de dados (ex.: Supabase) e autenticação, painel de cozinha privado e gestão de pedidos em tempo real.
4. Integração segura de pagamento (preferencialmente checkout hospedado e webhooks), sem guardar dados de cartão.
5. Clube de pontos controlado no servidor: acumular somente após pagamento confirmado, resgates atômicos, estornos e prevenção de fraude.
6. LGPD: política de privacidade, retenção e exclusão dos dados, segurança e controle de acesso.
7. Verificação de marca no INPI e validação operacional/comercial antes do lançamento.

## Regra sugerida MyDog Club

1 ponto por R$ 1 pago em itens elegíveis. 100 pontos para acompanhamento, 200 para desconto de R$ 10, 350 para The Original, 600 para combo surpresa. São propostas não vigentes; fixar validade, regras de acumulação e resgate antes da ativação.

## Teste local

Abra `index.html` em navegador para testar a navegação. PWA / service worker exige HTTPS ou localhost. Faça testes mobile e de produção após configurar o Pages.
