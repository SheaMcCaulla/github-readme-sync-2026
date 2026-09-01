---
title: Kuanza na Acme
---
<Accordion title="Hitilafu za Kawaida" icon="fa-info-circle">

</Accordion>

<Cards>
  <Card title="Usanidi wa Dakika 5" icon="fa-rocket">
    Kutoka ufunguo wa API hadi ombi la kwanza
  </Card>

  <Card title="Kuanza Haraka kwa API" icon="fa-code">
    Omba ufunguo wako wa API kutoka kwa timu yetu
  </Card>

  <Card title="Kadi ya Tatu" icon="fa-comments">

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