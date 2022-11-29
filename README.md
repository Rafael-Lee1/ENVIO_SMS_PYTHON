 ENVIO_SMS_PYTHON
 Envio de SMS  gratuito ,usando Python
 
 <div>
<img src="http://img.shields.io/static/v1?label=STATUS&message=%20FINALIZADO&color=GREEN&style=for-the-badge"/>
</div>
<div>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/f06aea2585a5ebb7c97ff88c1e3ec42fe92502fbd897abe4bf2e56eb7039e1aa/68747470733a2f2f63646e2e69636f6e2d69636f6e732e636f6d2f69636f6e73322f3131322f504e472f3531322f707974686f6e5f31383839342e706e67"><img src="https://camo.githubusercontent.com/f06aea2585a5ebb7c97ff88c1e3ec42fe92502fbd897abe4bf2e56eb7039e1aa/68747470733a2f2f63646e2e69636f6e2d69636f6e732e636f6d2f69636f6e73322f3131322f504e472f3531322f707974686f6e5f31383839342e706e67" alt="python" width="40" height="40" data-canonical-src="https://cdn.icon-icons.com/icons2/112/PNG/512/python_18894.png" style="max-width: 100%;"></a></p>
</div>


 Python e API com Login
# 
 O 1º Passo de toda API com Login é criar uma conta e pegar suas credenciais
# 
 No seu código, o 1º passo é sempre estabelecer a conexão com a API, usando seu login e suas credenciais
# 
 - Como cada API é uma ferramenta diferente, cada uma delas pode exigir que você faça algum tipo de configuração, que vai estar explicada na API. No nosso caso, teremos que validar um número e criar um número de envio
# 
 - Depois, usamos os métodos da API normalmente para fazer o que queremos. No nosso caso, enviar um SMS

 1. Vamos criar um login no Twilio
# 
 https://www.twilio.com/docs/libraries/python

 2. Depois do Login, vamos pegar 3 informações:
# 
 - ID da Conta
 - Token
 - Número de Envio

 3. Agora vamos validar um número porque no Twilio, enviar SMS para um número válido é de graça

 4. Agora podemos fazer o nosso código de acordo com as orientações do Twilio
