# <center> Desafio do Cenário Atual </center> 

As queimadas no Brasil destroem ecossistemas vitais nos biomas da Amazônia, Cerrado e Pantanal, entre outros, anualmente. O monitoramento reativo tradicional, apenas apagar o fogo após o início, gera custos econômicos massivos e perdas irreparáveis de biodiversidade. 
Conectando com a temática de Indústria Espacial, os fluxos de dados brutos gerados por satélites de sensoriamento remoto, como o GOES-16 e os sistemas do INPE, geram terabytes diários. O grande gargalo das instituições não é a falta de dados, mas sim, a capacidade de converter esses dados brutos de satélite em inteligência preventiva e preditiva. 



<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/5ce2d707-7618-4948-b57f-74ae9fb44a32" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/6bed7162-6756-4533-bfad-7f34a53aec30" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/84c99ef5-4ad0-4454-91d9-d15c114aac0d" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/63b519b7-fe68-4fec-bd2a-b85caaf7e163" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/e19aab39-66ce-4a72-b199-c8357285c2db" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/75e193d6-c48d-4fbf-8a9a-4fcac5e20846" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/97f47e54-f5ff-4668-8cc4-5fed0c750dea" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/b5c3116e-c8ab-44cf-8082-603d2d6a0fa7" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/739c460e-8ebb-4c6e-911e-b82d47576d21" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/9bd83628-56cc-4c30-a34e-6c822f042bbd" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/0f0e643f-931d-4e30-a124-dc56260ad3d5" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/7809af98-5cf5-4128-8fd7-0ac4035cc472" />


# Projeto: FIREDetect
Transformando Dados Orbitais em Inteligência Preventiva contra Queimadas

### 1. Introdução e Contexto

A indústria espacial evoluiu de um campo de exploração científica para um pilar estratégico da economia global. Com uma projeção de atingir US$ 1 trilhão até 2034, o verdadeiro desafio atual reside na transformação de dados brutos captados por constelações de satélites em soluções aplicáveis na Terra. No Brasil, esse cenário é crítico: anualmente, queimadas devastam biomas como a Amazônia, o Cerrado e o Pantanal, gerando perdas bilionárias e danos irreversíveis à biodiversidade.

O projeto FIREDetect surge como uma resposta tecnológica a esse gargalo, unindo Data Science e Inteligência Artificial para converter os terabytes de dados orbitais do INPE em previsões acionáveis.

### 2. O Problema: Monitoramento Reativo vs. Preditivo

Atualmente, as ações de combate ao fogo são predominantemente reativas. As equipes são mobilizadas apenas após o foco ser detectado, momento em que o dano ambiental já se iniciou.

Volume de Dados: Satélites como o GOES-16 geram dados contínuos, mas as instituições carecem de ferramentas que cruzem esses dados com variáveis climáticas em tempo real para antecipar o risco.

Impacto Econômico: Estimativas indicam que a logística brasileira perde entre 3% e 5% de sua eficiência devido a rupturas causadas por eventos climáticos, incluindo incêndios que bloqueiam vias e destroem ativos.

### 3. Solução Proposta: FIREDetect

O FIREDetect é uma plataforma de análise preditiva que utiliza modelos de Machine Learning (Random Forest e XGBoost) treinados com dados históricos e atuais de sensoriamento remoto.

Previsão de Risco: O sistema calcula o índice risco_fogo (0 a 1) para cada coordenada.

Intensidade de Queima: Utiliza a métrica FRP (Fire Radiative Power) para prever a severidade do incêndio em megawatts.

Variáveis Climáticas: Integra dados de precipitação e dias sem chuva para refinar a precisão, alcançando um R² de 0.85 no modelo Random Forest.
