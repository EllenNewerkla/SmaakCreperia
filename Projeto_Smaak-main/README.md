SMAAK CREPERIA - GESTÃO DE ESTOQUE E FINANSAS

Sistema de previsão de vendas, gerenciamento de estoque e controle financeiro para a Smaak Creperia, com uso de Machine Learning e integração com banco de dados Firebase, permitindo tomada de decisões estratégicas com base em dados históricos.

------------------------------------------------------------------------------------------------------------------

Funcionalidades 

- API em FastAPI com endpoints para: 
      - Gerar previsões de vendas para 7, 15, 30 e 60 dias.
      - Recuperar previsões otimizadas já salvas.
      - Analisar dados limpos com estatísticas detalhadas.
      - Verificar status do modelo e arquivos de dados.
- Implementação de algoritmo de séries temporais com Prophet.
- Armazenamento e consulta de previsões no Firebase Firestore.
- Hospedagem da API na nuvem (Railway App).


Tecnologias Utilizadas

- Python
- FastAPI
- Firebase (Firestore)
- Pandas, Prophet
- Railway (Deploy Cloud)


Como executar localmente
1 - git clone https://github.com/seu-usuario/Projeto_Smaak-main.git

2 - Abra dois terminais e escreva escreva 1 em cada:

'cd Projeto_Smaak-main' -> nos dois
cd BACKEND
cd FRONTEND

3 - Instale as dependencias
npm install
pip install uvicorn
python -m uvicorn main:app --reload
docker ps
ipconfig

4 - Configure o FireBase

- Crie um projeto no Firebase.
- Habilite o Authentication (por e-mail/senha).
- Crie um Realtime Database.
- Copie suas credenciais e adicione no arquivo firebaseConfig.js.

5 - Inicie o app
npx expo start

