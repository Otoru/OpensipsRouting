# Opensips

Script básico de roteamento de pacotes SIP utilizando OpenSips. Após a instalação, você deve ser capaz de usar este script de roteamento para realizar o roteamento de uma forma completa.

## Extrutura necessária

Para fazer uso desse script você deve ter os seguintes componentes instalados no servidor:

- OpenSips 3.0.x
- MySQL 5.7.x
- RTPEngine 7.5.x

**Observação**: Os testes estão sendo realizados em Debian 9.9.x

## Módulos configurados

- [nathelper](https://opensips.org/html/docs/modules/3.0.x/nathelper.html)
- [registrar](https://opensips.org/html/docs/modules/3.0.x/registrar.html)
- [rtpengine](https://opensips.org/html/docs/modules/3.0.x/rtpengine.html)
- [dialplan](https://opensips.org/html/docs/modules/3.0.x/dialplan.html)    
- [alias_db](https://opensips.org/html/docs/modules/3.0.x/alias_db.html)
- [drouting](https://opensips.org/html/docs/modules/3.0.x/drouting.html)
- [mi_fifo](https://opensips.org/html/docs/modules/3.0.x/presence.html)
- [auth_db](https://opensips.org/html/docs/modules/3.0.x/auth_db.html)
- [mi_fifo](https://opensips.org/html/docs/modules/3.0.x/mi_fifo.html)
- [mmgeoip](https://opensips.org/html/docs/modules/3.0.x/mmgeoip.html)
- [domain](https://opensips.org/html/docs/modules/3.0.x/domain.html)
- [dialog](https://opensips.org/html/docs/modules/3.0.x/dialog.html)
- [usrloc](https://opensips.org/html/docs/modules/3.0.x/usrloc.html)
- [httpd](https://opensips.org/html/docs/modules/3.0.x/httpd.html)
- [xcap](https://opensips.org/html/docs/modules/3.0.x/xcap.html)
- [pike](https://opensips.org/html/docs/modules/3.0.x/pike.html)
- [stun](https://opensips.org/html/docs/modules/3.0.x/stun.html)
- [acc](https://opensips.org/html/docs/modules/3.0.x/acc.html)
- [sst](https://opensips.org/html/docs/modules/3.0.x/sst.html)
- [rr](https://opensips.org/html/docs/modules/3.0.x/rr.html)
- [tm](https://opensips.org/html/docs/modules/3.0.x/tm.html)

## To-Do

- Adicionar módulo de Rate Limit.