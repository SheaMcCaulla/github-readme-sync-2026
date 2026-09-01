---
title: Primeiros passos com o Acme
---
<Accordion title="Erros Comuns" icon="fa-info-circle">

</Accordion>

<Cards>
  <Card title="Configuração em 5 Minutos" icon="fa-rocket">
    Da chave de API à primeira requisição
  </Card>

  <Card title="Início Rápido da API" icon="fa-code">
    Solicite sua chave de API à nossa equipe
  </Card>

  <Card title="Card Três" icon="fa-comments">

  </Card>
</Cards>

```mermaid
flowchart LR
  A[Request] --> B[Auth Check]
  B -->|Valid| C[200 Response]
  B -->|Invalid| D[401 Error]
```

<Banner
  isInline={true}
  message="This banner is displayed inline. Set isInline to false to move it seamlessly into your page's header!"
  color="#118cfd"
  textColor="#ffffff"
  fontSize="14px"
  fontWeight="bold"
 />