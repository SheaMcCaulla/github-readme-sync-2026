---
title: Erste Schritte mit Acme
---
<Accordion title="Häufige Fehler" icon="fa-info-circle">

</Accordion>

<Cards>
  <Card title="5-Minuten-Einrichtung" icon="fa-rocket">
    Vom API-Schlüssel bis zur ersten Anfrage
  </Card>

  <Card title="API-Schnellstart" icon="fa-code">
    Fordern Sie Ihren API-Schlüssel bei unserem Team an
  </Card>

  <Card title="Karte drei" icon="fa-comments">

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