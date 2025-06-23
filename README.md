# Projeto da criação de uma API com Azure API.
## Parte 1
No marketplace do Azure, digite na busca por APIM e procure por API Management.
![2025-06-22 (2)](https://github.com/user-attachments/assets/b2550eb6-a5df-4aa1-9933-b78463ac242a)
![2025-06-22 (3)](https://github.com/user-attachments/assets/f1b593c6-f0d6-4c87-9e13-7a8a7d9ea412)
Digite o que está sendo pedido como o grupo de recursos, a assinatura e as demais opções.
Na aba de monitormento e segurança seria melhor habilitar o monitoramneto por questões da API segura. 

## Parte 2
Aqui vai ser criado o Web APP
No marketplace do Azure, procure por 
![2025-06-22 (4)](https://github.com/user-attachments/assets/7eaad13a-42e0-4e49-8749-2750c33e53f6)
![2025-06-22 (5)](https://github.com/user-attachments/assets/14fd53f4-5773-4a5f-b0a3-a2c6170762ec)
Digite o que está sendo pedido.

## Parte 3
Vá no Web APP criado e na barra de pesquisa digite CORS.
Em Enable Access-Control-Allow-Credentials, habilite essa opção.

Em Allowed Origins, digite a url que está no API Management.

Selecione o botão de Salvar.

![2025-06-23](https://github.com/user-attachments/assets/609a2efa-020d-47ab-b1ec-dbfbc797d955)
![2025-06-23 (1)](https://github.com/user-attachments/assets/8c0904e1-0b5b-444d-838b-35d4451d4b94)

## Parte 4
No API Management, vá para APIs e selecione APIs.
![2025-06-23 (2)](https://github.com/user-attachments/assets/54b00390-20d2-4a18-9f6b-e629bd1e2778)
Vá para add ap e selecione APP Service
![2025-06-23 (3)](https://github.com/user-attachments/assets/6eedb0c1-cfc7-469e-9eda-0d8116b9c52f)
![2025-06-23 (4)](https://github.com/user-attachments/assets/76799abb-60db-4978-b10a-32311ad5adfb)
Preencha o que está sendo pedido.
![2025-06-23 (5)](https://github.com/user-attachments/assets/733cbe4b-8995-44ca-90d2-457ea062c373)
![2025-06-23 (6)](https://github.com/user-attachments/assets/e7b2eb6c-42d3-4911-a7f5-72b0912d5ba0)

## Parte 5
![2025-06-23 (7)](https://github.com/user-attachments/assets/911d8159-f6ab-4518-898b-e93d355ec987)
Depois vá em Rewrite URL
![2025-06-23 (8)](https://github.com/user-attachments/assets/bf927afe-ec99-4b97-8476-84df6e2bc57c)
Em backend digite weatherforecast e aperte em salvar
![2025-06-23 (9)](https://github.com/user-attachments/assets/238b3380-36e8-4263-af74-98aa74f26067)
Procure por subscription e onde tiver Header name e Query parameter name, digite x-api-key
![2025-06-23 (10)](https://github.com/user-attachments/assets/69a5d690-0529-4777-b06e-3b3503dfb13c)
Agora crie uma nova subscription. Depois de criada, copie a Primary key e guarde ela para uso futuro.
![2025-06-23 (11)](https://github.com/user-attachments/assets/0ba4e18d-a41b-45a2-8dcf-fc76f38d229e)

