# Calm Wave

![Calm Wave Logo](https://via.placeholder.com/150) **Reduzindo o ruído para um aprendizado sem barreiras.**

Calm Wave é uma aplicação inovadora projetada para criar ambientes de aprendizado mais inclusivos e eficazes para crianças com Transtorno do Processamento Auditivo Central (TPAC) e hipersensibilidade auditiva. Nossa solução utiliza inteligência artificial para eliminar ruídos de fundo em tempo real, permitindo que os alunos se concentrem no que realmente importa: a voz do professor.

## O Problema

Em ambientes com alta poluição sonora, como salas de aula, crianças com sensibilidade auditiva enfrentam uma sobrecarga sensorial que pode comprometer drasticamente a concentração, o aprendizado e o bem-estar emocional. O Transtorno do Processamento Auditivo Central (TPAC) e outras condições, como o Transtorno do Espectro Autista (TEA), exacerbam esses desafios, tornando a tarefa de processar informações auditivas uma batalha constante.

## Nossa Solução

O Calm Wave oferece uma solução tecnológica que atua como um filtro inteligente entre o professor e o aluno. Através de um aplicativo, o áudio do ambiente é captado, processado e entregue de forma limpa e clara para a criança, proporcionando uma experiência de aprendizado mais tranquila e focada.

## Como Funciona

Nossa arquitetura foi desenhada para ser eficiente e escalável, garantindo um áudio limpo com o mínimo de latência.

1.  **Captação de Áudio:** O microfone do dispositivo do professor captura a voz e os sons do ambiente.
2.  **Processamento no Front-End:** O áudio é segmentado em pequenos `chunks` (pacotes) para otimizar o processamento.
3.  **API e Microserviço de IA:** Os `chunks` são enviados para nossa API, que os direciona para um microserviço de Inteligência Artificial.
4.  **Redução de Ruído:** A IA analisa o áudio, identifica e elimina ruídos externos indesejados, preservando a clareza da voz do professor.
5.  **Entrega de Áudio Limpo:** O áudio tratado é devolvido ao dispositivo do aluno, que o escuta através de fones de ouvido.

## Principais Funcionalidades

- **Redução de Ruído em Tempo Real:** Filtra distrações sonoras para maximizar a concentração.
- **Foco na Voz do Educador:** Isola e prioriza a fala, facilitando a compreensão.
- **Interface Simples e Amigável:** Desenhado para ser intuitivo tanto para crianças quanto para educadores.
- **Melhora na Qualidade de Vida:** Reduz a sobrecarga sensorial, promovendo bem-estar e melhorando o desempenho acadêmico.
- **Apoio a Educadores:** Oferece uma ferramenta poderosa para criar um ambiente de sala de aula mais inclusivo.

## Tecnologias Utilizadas

O Calm Wave é construído sobre uma base tecnológica moderna e robusta, utilizando as melhores ferramentas para cada parte do sistema.

- **Back-End (IA e API):** `Python`
- **Aplicativo Android:** `Kotlin`
- **Front-End (Web):** `TypeScript`

## Como Contribuir

Estamos comprometidos com a inovação contínua e acreditamos no poder da comunidade. Se você é especialista, desenvolvedor, educador ou cuidador, sua contribuição é fundamental para o sucesso do projeto.

- **Reportando Bugs:** Encontrou um problema? Abra uma *issue* em nosso repositório.
- **Sugestão de Funcionalidades:** Tem ideias para melhorar o Calm Wave? Adoraríamos ouvi-las!
- **Desenvolvimento:** Faça um *fork* do projeto e envie um *pull request* com suas melhorias.

## Agradecimentos

Agradecemos o seu interesse e apoio ao projeto Calm Wave. Juntos, podemos criar um mundo onde cada criança tenha a oportunidade de aprender sem barreiras.
