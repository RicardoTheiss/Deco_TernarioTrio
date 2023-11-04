## Prezados membros da banca avaliadora e demais partes interessadas,

É com grande entusiasmo que apresentamos o projeto desenvolvido pela equipe "Trio Ternário" na plataforma Deco, fazendo uso do ambiente Deco Play. Nosso objetivo foi enriquecer a experiência de compra do usuário. A partir de um componente que possibilita ao lojista facilmente implementar pequenos questionários binários ao cliente, usamos os dados de resposta como parâmetros para moldar uma experiência e navegação mais segmentada e direcionada.

# Exemplo aplicado e Visão Geral do Projeto:

O exemplo em questão consiste em um e-commerce que oferece uma seleção de roupas e itens baseada nas respostas do usuário a pequenas perguntas sobre seu clima preferido e seu estado emocional no momento. Além do componente que desenvolvemos, que permite criar esses pequenos questionários facilmente diretamenta na interface do CMS da Deco, utilizamos a tecnologia dos Matchers da plataforma Deco, em especial os matchers de Weather e Cookies, para realizar a segmentação.

# Expandindo:

Lógicamente, além dos contextos em que foram aplicados neste exemplo, o componente permite que sejam realizadas as mais diversas perguntas ao usuário/cliente, para que assim esses dados possam ser usados para compor seu perfil de consumo. Como recomendação de uso, entendemos que essas perguntas/questões/opções deveriam sempre manter um tom alegre e bem humorado, de modo que sejam vistas pelo usuário/cliente como um ponto positivo durante sua navegação e não como um empecilho.

# Detalhes Técnicos e Funcionamento

## Componente AskUserPreference (section)
Recebe como props um título, duas opções de respostas e o nome do cookie que será criado para essa preferência bem como uma data de expiração (opcional).

## Componente CookieSetter (island)
Recebe como props os dados da opção de resposta. Executa função que cria os cookies com os dados recebidos.

## Consumo dos cookies com matchers
Fazendo uso dos matchers presentes na plataforma Deco.cx, em especial o CookieMatcher, são definidas seções segmentadas de acordo com as respostas dos usuários/clientes. Essa segmentação pode se dar de várias formas, seja com a exibição apenas de produtos específicos que atendam a determinados critérios, até mesmo ao uso de uma linguagem de comunicação mais segmentada, como mensagens publicitárias que encaixem melhor com o público delimitado.

# Limitações
Nós, como equipe "Trio Ternário," reconhecemos algumas limitações inerentes ao nosso projeto. Em primeiro lugar, nossa equipe enfrentou desafios consideráveis devido à falta de experiência com a nova stack tecnológica e a complexidade da plataforma Deco, que representaram uma curva de aprendizado íngreme. Além disso, a ideia em si, embora promissora, pode não ser a mais otimizada, já que ainda estamos aprimorando nossa compreensão das necessidades dos usuários e das melhores práticas de segmentação. Portanto, nosso projeto é uma exploração inicial que requer refinamentos contínuos para atingir seu potencial máximo.

# Agradecimentos
Gostaria de expressar meu sincero agradecimento ao nosso professor Ivan e aos membros da equipe Hackaton Deco, em especial ao Gaudencio e ao Mcandeia. Seu apoio e contribuição foram fundamentais para o sucesso deste projeto. Muito obrigado!

Agradeço a todos os demais envolvidos neste projeto. 
Nossa jornada foi repleta de desafios, mas juntos, alcançamos (alguns de) nossos objetivos. 
A dedicação de cada membro da equipe foi essencial para o sucesso. 



Atenciosamente,
Trio Ternário