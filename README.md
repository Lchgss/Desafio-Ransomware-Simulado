# Desafio-Ransomware-Simulado
Desafio da DIO para criar um ransomware

Todos os arquivos criados no projeto estarão disponiveis no repositorio

## Iniciando o projeto

Para começar o projeto, precisamos de uma pasta onde os arquivos vão estar armazenados

Abra o CMD do Kali e crie uma pasta para o projeto. A pasta criada abaixo tem o caminho /Downloads/ransom

![image](https://github.com/user-attachments/assets/cced6769-cc77-4870-b233-8b3b56e1d39d)

Não esqueça de instalar o pyaes com o comando "sudo apt install python3-pyaes"

## CRIPTOGRAFANDO

Para criar um arquivo de texto para criptografar digite "nano + nome do arquivo"

No projeto abaixo foi usado "nano encripta.py"


Importe as bibliotecas os e pyaes

![image](https://github.com/user-attachments/assets/bb6dd8ae-34fb-453f-b53d-335c6deacc0f)

O codigo abaixo vai abrir o arquivo para criptografar

![image](https://github.com/user-attachments/assets/f519eab4-ec7c-4e22-8ed4-7d0c23f02821)

O codigo abaixo vai remover o arquivo original

![image](https://github.com/user-attachments/assets/6451b0f4-c70c-464f-a2ee-670cae967924)

O codigo abaixo vai definir a chave de criptografia

![image](https://github.com/user-attachments/assets/48b60c89-d1ac-4ee0-86ce-a602595dc4da)

O codigo abaixo vai criptografar o arquivo

![image](https://github.com/user-attachments/assets/d200ca51-02fa-497d-bb53-b5d70ecb9257)

O codigo abaixo vai salvar o arquivo depois de criptografado

![image](https://github.com/user-attachments/assets/43d2c56f-a8e4-49a5-88aa-cda731ba2f79)

Salve o arquivo com CTRL + O e saia dele com CTRL + X

## DESCRIPTOGRAFANDO

Para criar o arquivo que vai descriptografar o arquivo digite "nano + nome do arquivo"

No projeto abaixo foi usado "nano resolve.py"

Importe novamente as bibliotecas os e pyaes

![image](https://github.com/user-attachments/assets/30ba2656-c7c4-4cbf-8e26-5be9fc166a74)

O comando abaixo vai abrir o arquivo criptografado

![image](https://github.com/user-attachments/assets/55bee24d-41e6-44a6-bb30-368d288c13d4)

O codigo abaixo vai definir a chave descriptadora

![image](https://github.com/user-attachments/assets/62173a2a-1f94-4f47-8edb-8adcd47a1bc3)

O codigo abaixo vai remover o arquivo criptografado

![image](https://github.com/user-attachments/assets/f0ebff60-bb72-4687-81da-5869ca35bb76)

O codigo abaixo vai salvar o arquivo descriptografado

![image](https://github.com/user-attachments/assets/15413768-6667-482a-a53c-69ea2bd81595)

Salve o arquivo com CTRL + O e saia dele com CTRL + X


## Resultados

O arquivo de teste recebeu o nome teste.txt e estava com a seguinte mensagem

![image](https://github.com/user-attachments/assets/60ef3934-8b18-41cc-855d-50e3c527c5f0)

E na pasta ele aparecia assim:

![image](https://github.com/user-attachments/assets/af6622f7-03ed-466f-b078-1c0657a95af5)

Para criptografar ele foi chamado o arquivo de criptografia "encripta.py" com o comando "python encripta.py"

![image](https://github.com/user-attachments/assets/6d15a4ad-620d-48de-8d25-7ad5ef1ae5ca)

Depois de encriptar, a estrutura dos arquivos estava assim

![image](https://github.com/user-attachments/assets/93832970-e553-49d9-bb22-bba1594fe9d6)

E o arquivo ficou ficou assim na pasta

![image](https://github.com/user-attachments/assets/e65f1484-79c1-42ed-9469-1bd1a18a6f3e)

E ao tentar abrir ele com comando nano ele mostrava isso

![image](https://github.com/user-attachments/assets/51fca7f2-afbf-43a3-ae84-639c9f29d0bc)

Para descriptografar ele vamos usar o arquivo "resolve.py" com o comando "python encripta.py"

![image](https://github.com/user-attachments/assets/7011ec3e-ea3b-495b-942d-bcc8342b46af)

Podemos ver que o arquivo de texto aparece normal na estrutura dos arquivos

![image](https://github.com/user-attachments/assets/14e56c3f-2191-4c87-9a7d-0a5547dbc9ae)

E que na pasta ele está assim

![image](https://github.com/user-attachments/assets/fdc0c993-f788-450e-81dc-2e89543dddb6)

Por fim, ao usar o comando nano podemos ver o conteúdo do texto novamente sem problemas

![image](https://github.com/user-attachments/assets/921e3fb9-971c-4bc2-89ae-9646f4eb0108)
