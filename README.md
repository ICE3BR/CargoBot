# CargoBot
Um Mini Robô de Transporte Baseado em Arduino

# Tema
Mini AGV (Automated Guided Vehicle) para Transporte Logístico com Arduino ou Desenvolvimento de um Robô Seguidor de Linha com Arduino para Aplicações Logísticas


# Introdução
Com o crescimento da automação industrial, robôs móveis autônomos têm sido amplamente utilizados para otimizar processos logísticos. Os **AGVs (Automated Guided Vehicles)** são exemplos de robôs que seguem trajetos predefinidos para transportar cargas em armazéns e fábricas, aumentando a eficiência e reduzindo a necessidade de intervenção humana.

Inspirado nessa tecnologia, este projeto propõe a construção de um **robô seguidor de linha** simples, utilizando **Arduino** e sensores infravermelhos para navegar por um trajeto determinado. O objetivo principal é garantir um deslocamento estável e eficiente, servindo como base para futuras melhorias, como a implementação de um **sistema de carga e descarga**.

## Objetivo Geral
Desenvolver um **robô seguidor de linha** baseado em **Arduino Uno R3 ou Arduino Nano**, capaz de percorrer um trajeto predefinido de forma autônoma, utilizando sensores para navegação precisa.

### Objetivos Específicos
1. Construir a estrutura física do robô utilizando materiais acessíveis e de baixo custo.
2. Implementar um **sistema de controle** para navegação autônoma baseado em sensores infravermelhos.
3. Desenvolver e otimizar o **código de programação em C/C++** para garantir um bom desempenho no rastreamento da linha.
4. Testar e validar o funcionamento do robô em diferentes trajetos e condições de iluminação.
5. Documentar o projeto detalhadamente, publicando o código e as instruções no **GitHub** e outras plataformas acadêmicas.
6. Possivelmente, aprimorar o robô futuramente adicionando um sistema de **carga e descarga** para simular um AGV industrial.

## Justificativa
Os **robôs seguidores de linha** são amplamente utilizados para aplicações educacionais e experimentação em automação. A construção desse projeto permitirá explorar conceitos importantes de robótica, eletrônica e programação embarcada, além de servir como uma base para futuras melhorias.

Além disso, o desenvolvimento de um **protótipo de AGV em pequena escala** pode demonstrar como soluções de automação podem ser implementadas de forma acessível, abrindo caminho para aplicações mais avançadas no futuro.

## Metodologia
1. **Planejamento do Hardware:** Escolha dos componentes eletrônicos, como sensores IR, motores DC, driver de motor (ponte H) e estrutura do robô.
2. **Montagem do Robô:** Fixação dos componentes e construção do chassis utilizando materiais simples como acrílico, MDF ou papelão.
3. **Desenvolvimento do Software:** Programação do Arduino para interpretar os sensores e controlar os motores.
4. **Testes e Ajustes:** Testes em diferentes trajetos para calibrar os sensores e otimizar a resposta do robô.
5. **Documentação e Divulgação:** Publicação do código-fonte e documentação no GitHub e possíveis artigos acadêmicos.

## Tecnologias e Ferramentas Utilizadas
- **Microcontrolador:** Arduino Uno R3 ou Arduino Nano
- **Sensores:** Sensores infravermelhos (IR) para detecção da linha
- **Atuadores:** Motores DC com driver Ponte H (L298N)
- **Estrutura:** Chassi de material acessível (papelão, acrílico, MDF)
- **Programação:** C/C++ utilizando a IDE do Arduino
- **Documentação:** Repositório no GitHub, ORCID e Zenodo

## Possíveis Melhorias Futuras
- Implementação de um **módulo de carga e descarga**, tornando o robô uma simulação realista de um **AGV industrial**.
- Uso de sensores ultrassônicos para evitar obstáculos e melhorar a navegação.
- Integração com um sistema de **controle remoto via Bluetooth ou Wi-Fi**.
- Desenvolvimento de um **algoritmo de inteligência artificial** para otimizar a trajetória.

## Conclusão
Este projeto fornecerá uma base sólida para o aprendizado em robótica e sistemas embarcados, sendo um primeiro passo para a construção de um **AGV autônomo**. Com o funcionamento básico garantido, futuras melhorias poderão ser implementadas para expandir suas capacidades.

## Próximos Passos:
1. **Definir a lista de componentes** necessários para o primeiro protótipo.
2. **Criar um diagrama de montagem** para facilitar a construção.
3. **Escrever o código inicial do Arduino** para testes básicos de movimentação.
