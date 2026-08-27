# Aula---01---Sistemas-Distribuidos

Abra o Prompt de Comando
No Windows:
1. Pressione Windows + R;
2. Digite:
cmd
3. Pressione Enter.
Não feche o Prompt de Comando.

------------------------------
No Prompt de Comando, execute:
ping google.com
Observe o resultado.
Você deverá encontrar informações como:
● endereço IP;
● tempo aproximado de resposta;
● pacotes enviados;
● pacotes recebidos;
● pacotes perdidos.

------------------------------
1. Qual endereço IP apareceu?
2. Quantos pacotes foram enviados?
3. Quantos foram recebidos?
4. Houve perda de pacotes?
5. Qual foi aproximadamente o tempo de resposta?

----------------------------
No mesmo Prompt de Comando, execute:
nslookup google.com
Observe o resultado.
Identifique:
Nome consultado:
Endereço(s) IP encontrado(s):
Agora tente:
nslookup youtube.com

-------------------------------
Agora execute:
tracert google.com
Aguarde a execução.
O comando mostrará os saltos (hops)
realizados no caminho até o destino.
Observe:

-----------------------------------
1. Quantos saltos apareceram?
2. Todos responderam?
3. Apareceu * * * em algum salto?
4. O seu computador está conectado diretamente ao servidor do Google?

-----------------------------------
O QUE APRENDEMOS COM O
EXPERIMENTO?
Com apenas três comandos:
ping
nslookup
tracert
já conseguimos perceber alguns elementos fundamentais de ambientes distribuídos.
Nossa comunicação depende de:
Identificação
Endereços permitem identificar destinos na rede.
