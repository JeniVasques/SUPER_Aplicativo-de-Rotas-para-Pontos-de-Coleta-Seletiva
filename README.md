# Rotas para Pontos de Coleta Seletiva – Manaus

Aplicativo Android que mostra os pontos de coleta de recicláveis em Manaus
e traça a rota até o ponto escolhido. Desenvolvido no Projeto Super, na UFAM,
entre 2024 e 2025, para incentivar o descarte correto de recicláveis e
facilitar o acesso à informação sobre coleta seletiva na cidade.

## Funcionalidades
- Mapa com os pontos de coleta seletiva de Manaus
- Rota até o ponto de coleta selecionado ou o mais próximo, via Google Maps
- Localização do usuário em tempo real no mapa
- Interface simples, pensada para quem não tem familiaridade com tecnologia

## Tecnologias
- Kotlin · Android Studio
- Google Maps API (mapa, localização e rotas)
- Firebase Firestore (dados dos pontos de coleta)

## Como rodar
1. Clone o repositório e abra a pasta no Android Studio.
2. Crie um projeto no Firebase e coloque o seu arquivo `google-services.json` na pasta `app/`.
3. Gere uma chave da Google Maps API no Google Cloud e adicione no arquivo `local.properties`:
   `MAPS_API_KEY=sua_chave`
4. Rode o app em um emulador ou em um celular Android.

## Minha participação
Projeto desenvolvido em equipe. Fui responsável por:
- Tela de entrada do aplicativo
- Integração com a Google Maps API: exibição do mapa, localização do
  usuário e traçado de rotas até os pontos de coleta
- Testes funcionais e exploratórios: identifiquei falhas e propus
  melhorias na experiência do usuário

## O que aprendi
- Integrar um aplicativo a uma API externa e lidar com permissões de localização no Android
- Trabalhar em equipe com Git, dividindo funcionalidades entre os integrantes
- Testar o app do ponto de vista do usuário para encontrar problemas antes da entrega
