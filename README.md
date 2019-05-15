# Teste de emprego: Aplicativo de Realidade Aumentada
## Introdução
O projeto consiste em um simples aplicativo, que ao ser aberto, apresentará algumas opções de experiências de realidade aumentada para o usuário. O usuário escolherá a que lhe convém, e o aplicativo se comunicará com uma API-Backend para baixar os assets necessários da experiência escolhida pelo usuário.

## Técnologias que deverão ser utilizadas
- **Engine**: `Unity Engine 2018.3.4f1`(**Não serão aceitos projetos feitos em versões diferentes**). Você poderá baixar essa versão da unity [através deste link.](https://download.unity3d.com/download_unity/1d952368ca3a/UnityDownloadAssistant-2018.3.4f1.exe "através deste link.")
- **AR SDK:** `Vuforia`

## Objetivo
O objetivo desse teste é avaliar as habilidades do aplicante com: 
- **Unity**: Verificar as habilidades do aplicante com a Unity;
- **Código**: Verificar as habilidades do aplicante programando. Serão avaliados o estilo de código, perfomance, boas-práticas e o uso de SOLID.
- **Conhecimento geral sobre as técnologias que serão utilizadas diariamente**: `Unity, Vuforia & C#` e como eles podem ser utilizados juntos, para criar um app de realidade aumentada.

## O aplicativo
### Primeira Tela(Menu & Carregamento)
- Ao abrir o aplicativo, será exibido uma lista para o usuário com 3 botões. Cada botão representará uma experiência em realidade aumentada para o usuário, sendo eles: 
 - Realidade Aumentada no cartão de visitas
 - Realidade Aumentada em desenhos
 - Realidade aumentada em Camisetas

**Obs:** Somente a primeira realidade aumentada(Cartão de visitas) deverá ser feita, 
as restante não serão necessárias. 

- Após clicar no botão da Realidade Aumentada no Cartão de Visitas, o aplicativo deverá baixar o seguinte vídeo: https://whatsnextdigital.com.br/cdn/Shared/videos/whatsnextdigital_video.mp4

 - Durante o download do vídeo, deverá ser mostrado para o usuário, uma tela de carregamento, com o progresso do download. Caso o download falhe, nessa mesma tela deverá ser exibido um  botão para tentar fazer o download novamente. 
 
**Obs:** Após baixado, o vídeo deverá ser armazenado localmente, e na próxima vez que o usuário clicar no botão, o vídeo deverá ser carregado do Cache. 


### Segunda Tela(Realidade Aumentada)
Consistirá em uma tela simples, onde será exibido a câmera do celular, e um botão para voltar a tela anterior. 

O **target** utilizado na realidade aumentada, deverá ser este: 
[![Target da Realidade Aumentada](https://github.com/whatsnext-digital/ar-interview-exam/blob/master/assets/whatsnext_marcador.jpg "Marcador da Realidade Aumentada")](https://github.com/whatsnext-digital/ar-interview-exam/blob/master/assets/whatsnext_marcador.jpg "Marcador da Realidade Aumentada")

Ao apontar a câmera do celular para este Target, o vídeo baixado anteriormente deverá ser exibido, com as seguintes funcionalidades: 
1. Ao tocar no vídeo, ele deverá ser pausado/despausado;
2. Quando o target for perdido, o vídeo deverá ser pausado automáticamente;
3. Quando o target for achado novamente, o vídeo deverá ser tocado automáticamente.

## Sobre o exame
Os aplicantes estão autorizados a usarem bibliotecas externas e montarem a estrutura da aplicação da forma que acharem melhor. Sinta-se livre para usar a internet para fazer pesquisas, mas não será permitido utilizar e/ou adaptar códigos/projetos da internet,  pois desta forma não conseguiremos avaliar sua habilidade técnica.

### O que não será considerado:
- **Design**: Não se preocupe com visual, animações ou "deixar bonito", pois esses pontos não serão avaliados.
- **Segurança**: Não é necessário criptografar nenhum tipo de dados, ou se preocupar com vazamento de informações, autênticação ou autorização. 

