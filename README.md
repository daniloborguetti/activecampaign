Envie informações do evento ActiveCampaing com GTM por meio de um proxy do Google Cloud Functions.

Descrição
Envie dados de rastreamento de eventos para ActiveCampaign com o Google Tag Manager e uma função do Google Cloud. Você precisará configurar:

A função Google Cloud
O rastreamento GTM com o modelo de rastreamento de eventos ActiveCampaign
Uma forma de identificar o usuário (identificadores de usuário: e-mail, hash de usuário ActiveCampaign, ID de contato ActiveCampaign)

Teste
Use esta string de consulta anexada ao URL do Cloud Functions
?action=trackEvent&eventName=EVENTNAME&eventData=EVENTDATA&contactId=CONTACTID

Substitua EVENTNAME, EVENTDATA e CONTACTID pelos seus dados fictícios
