 ENVIO_SMS_PYTHON
 Envio de SMS  gratuito ,usando Python

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
