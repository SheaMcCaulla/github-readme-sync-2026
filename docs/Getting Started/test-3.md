---
title: Acme を始める
---
<Accordion title="よくあるエラー" icon="fa-info-circle">

</Accordion>

<Cards>
  <Card title="5分セットアップ" icon="fa-rocket">
    APIキーの取得から最初のリクエストまで
  </Card>

  <Card title="APIクイックスタート" icon="fa-code">
    チームにAPIキーをリクエストする
  </Card>

  <Card title="カード3" icon="fa-comments">

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