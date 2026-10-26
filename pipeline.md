# Pipeline de Feedback Contínuo - Cultura DevOps

Este repositório contém o código e a configuração da esteira de integração desenvolvidos no âmbito da disciplina de Desenvolvimento de Sistemas (Aula 2 - Código: SISANO1C3B4S21A2). O projeto foca-se na aplicação prática dos pilares da programação orientada a objetos e da cultura DevOps.

O objetivo central desta implementação é validar o código a cada alteração submetida, garantindo integração contínua, testes automatizados e a notificação de falhas em menos de 5 minutos.

## 🚀 Funcionalidades da Esteira (Pipeline)

O fluxo automatizado foi desenhado para suportar a mentalidade *fail fast*, descobrindo falhas o mais rapidamente possível para reduzir o *lead time* e o custo de correção. O pipeline divide-se nas seguintes etapas cruciais:

* **Build (Construção):** Compila e prepara o código, garantindo que a aplicação é montada corretamente no ambiente.


* **Test (Testes):** Executa os testes automáticos (unitários e de integração) para validar a lógica e impedir que código defeituoso avance.


* **Monitor (Monitorização):** Acompanha os resultados da esteira e envia alertas automáticos para a equipa.



## 🛠️ Tecnologias Utilizadas

* **GitHub Actions:** Ferramenta de CI/CD utilizada para orquestrar o pipeline, disparando o fluxo a cada *commit* e devolvendo um estado visual imediato (*badges*) de sucesso ou erro.


* (Adicione aqui a linguagem de programação utilizada, ex: Java, Python, Node.js)
* (Adicione aqui o *framework* de testes, ex: JUnit, Jest, PyTest)

## 📌 Diagnóstico DORA e Melhoria Contínua

Este repositório serve também como base para análises de diagnóstico de desempenho da equipa (Métricas DORA), permitindo desenhar fluxos de trabalho, identificar potenciais gargalos e tomar decisões técnicas que aprimorem a segurança e a agilidade nas entregas.
