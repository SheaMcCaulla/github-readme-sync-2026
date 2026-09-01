---
title: Aan de slag met Acme
---
<Accordion title="Veelvoorkomende fouten" icon="fa-info-circle">

</Accordion>

<Cards>
  <Card title="Installatie in 5 minuten" icon="fa-rocket">
    Van API-sleutel tot eerste verzoek
  </Card>

  <Card title="Snelstart API" icon="fa-code">
    Vraag uw API-sleutel aan bij ons team
  </Card>

  <Card title="Kaart drie" icon="fa-comments">

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