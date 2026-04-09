# Bingo System: Arquitetura Observer & Lean 🎰

Este projeto é uma implementação técnica de um sistema de sorteio de Bingo desenvolvido em **Java**. O diferencial deste trabalho não é apenas a funcionalidade, mas a aplicação rigorosa de padrões de arquitetura para garantir um código limpo e escalável.

## 🏗️ Padrões de Design: Observer
A principal característica técnica deste projeto é o uso do **Padrão Observer**. 
- **O Problema:** Como atualizar múltiplas cartelas (observadores) sempre que um novo número é sorteado (sujeito) sem criar um código dependente e confuso?
- **A Solução:** Implementação de uma interface que permite ao sorteador notificar automaticamente todas as instâncias ativas, garantindo o desacoplamento total entre a lógica de sorteio e a interface visual.

## 🛠️ Tecnologias e Metodologias
- **Linguagem:** Java (JDK 17+)
- **Interface Gráfica:** Java Swing
- **Metodologia Lean:** Aplicação do conceito de MVP (Minimum Viable Product), focando na estabilidade do sorteio e na experiência do utilizador antes da expansão de funcionalidades.

## 📂 Documentação
O detalhamento da arquitetura, incluindo diagramas de classe e a fundamentação teórica sobre baixo acoplamento, pode ser consultado no documento abaixo:
* [📄 Relatório Técnico - Arquitetura de Software (PDF)]([./Jogo_de_Bingo_Java_Observer.pdf](https://github.com/eumanuelalobo/java-bingo-observer-system/blob/ae04bacc731a06dbf3e00ee791f330756e88deba/Jogo%20de%20Bingo%20em%20Java_%20Arquitetura%20Observer%20e%20Otimiza%C3%A7%C3%A3o%20com%20Lean.pdf))

---
**Desenvolvido por:** Manuela Lobo  
*Foco em Arquitetura de Sistemas e Engenharia de Software.*
