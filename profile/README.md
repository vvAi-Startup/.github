# Calm Wave

<img width="500" height="500" alt="Fones_e_Onda_Minimalista__1_-removebg-preview 3" src="https://github.com/user-attachments/assets/7f120e2f-6f50-4972-a1b0-bdc9f3911c1c" /> **Reduzindo o ruído para um aprendizado sem barreiras.**

Calm Wave é uma aplicação inovadora projetada para criar ambientes de aprendizado mais inclusivos e eficazes para crianças com Transtorno do Processamento Auditivo Central (TPAC) e hipersensibilidade auditiva. Nossa solução utiliza inteligência artificial para eliminar ruídos de fundo em tempo real, permitindo que os alunos se concentrem no que realmente importa: a voz do professor.

## O Problema

Em ambientes com alta poluição sonora, como salas de aula, crianças com sensibilidade auditiva enfrentam uma sobrecarga sensorial que pode comprometer drasticamente a concentração, o aprendizado e o bem-estar emocional. O Transtorno do Processamento Auditivo Central (TPAC) e outras condições, como o Transtorno do Espectro Autista (TEA), exacerbam esses desafios, tornando a tarefa de processar informações auditivas uma batalha constante.

## Nossa Solução

O Calm Wave oferece uma solução tecnológica que atua como um filtro inteligente entre o professor e o aluno. Através de um aplicativo, o áudio do ambiente é captado, processado e entregue de forma limpa e clara para a criança, proporcionando uma experiência de aprendizado mais tranquila e focada.

## Diferencial Técnico: Processamento Offline
Diferente de soluções convencionais que dependem de processamento em nuvem, o Calm Wave prioriza a privacidade e a baixa latência através do uso de modelos ONNX (Open Neural Network Exchange) integrados diretamente ao dispositivo. Isso garante que o áudio seja processado localmente, eliminando a necessidade de conexão constante com a internet e reduzindo drasticamente o tempo de resposta entre a fala do professor e a recepção pelo aluno.

## Como Funciona

Nossa arquitetura foi otimizada para performance em dispositivos móveis:

1. **Captação**: O microfone do dispositivo captura o fluxo de áudio ambiente.
2. **Segmentação**: O áudio é tratado em chunks de baixa latência para garantir fluidez.
3. **Inferência Local**: Utilizamos modelos em formato ONNX rodando nativamente no Android.
4. **Redução de Ruído**: A rede neural identifica padrões de voz e suprime frequências de ruído de fundo (como conversas paralelas, cadeiras arrastando e zumbidos da sala).
5. **Output**: Áudio limpo entregue em tempo real para o fone de ouvido do usuário.

## Principais Funcionalidades

- **Denoising via ONNX**: Processamento offline de alta performance.
- **Baixa Latência**: Ideal para o uso em tempo real em sala de aula.
- **Interface Inclusiva**: Focada na experiência do usuário final, considerando as necessidades sensoriais das crianças.
- **Independência de Rede**: Funciona perfeitamente mesmo em ambientes escolares sem Wi-Fi estável.

## Tecnologias Utilizadas

O ecossistema Calm Wave é sustentado por um stack técnico robusto e focado em eficiência:

- **Mobile (Android)**: Desenvolvido em Kotlin com Jetpack Compose para uma interface fluida e acessível.
- **Inteligência Artificial**: Modelos de processamento de áudio convertidos e otimizados via ONNX Runtime.
- **Back-End/Suporte**: Python utilizado para experimentação, treinamento de modelos e pipeline de pré-processamento.
- **Front-End (Web)**: TypeScript para documentação e painéis de controle do projeto.
  
## Como Contribuir

Acreditamos na tecnologia como ferramenta de inclusão. Se você quer nos ajudar a tornar o aprendizado mais acessível:

- **Desenvolvimento Mobile**: Explore nosso repositório em Kotlin/Jetpack Compose.
- **Otimização de IA**: Ajuda com modelos ONNX e técnicas de quantização de áudio são muito bem-vindas.
- **Feedback**: Reporte problemas ou sugira melhorias através de issues no GitHub.

## Agradecimentos

Agradecemos a todos que apoiam o desenvolvimento do Calm Wave. Com o seu suporte, estamos transformando a tecnologia em um meio para que cada criança tenha a oportunidade de aprender sem barreiras sonoras.
