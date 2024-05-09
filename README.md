import request
import json

link = https://discord.com/api/webhooks/1237923894078341201/BAuf0q62Z6eILpDyIdkKBEamEBU5eVruWmCAJ87accCnJWtmlwDA0JO_zRlge6qQvcNT

dicionario = {
<a:V_red_alerta:707384234951704577>  Regras diretoria SPK <a:V_red_alerta:707384234951704577> 
```●```
> Regras da área e do servidor:
```●```
> <a:alert_Spk:1053006339770679470>  Proibido Discussões não relacionadas a staff
> 
> <a:alert_Spk:1053006339770679470>  Proibido qualquer tipo de discurso de ódio
> 
> <a:alert_Spk:1053006339770679470>  Imparcialidade perante todas as áreas do servidor
> 
> <a:alert_Spk:1053006339770679470>  Ativo durante a semana
> 
> <a:alert_Spk:1053006339770679470>  Respeito com todos independente do cargo
> 
> <a:alert_Spk:1053006339770679470> Proibido recrutar sem a permissão do <@&1150926476397518869> ou <@&1150929850870267924> 
```●```
> <:Sim:1204776708297723914> Cumprir com as diretrizes do discord
> 
> <:Sim:1204776708297723914> Proatividade com as áreas
> 
> <:Sim:1204776708297723914> Manter os chats de relatórios atualizados diariamente
```●```
> ||<@&1214032665884499988>  / <@&1152666358899818638> ||
> }
> dicionario_ajustado = json.dumps(dicionario)
> request.post(link, data=dicionario_ajustado)
