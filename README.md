# AryIN

Projeto de Faculdade - Desenvolvimento Fullstack
Este repositório contém um projeto desenvolvido para uma atividade acadêmica, com o objetivo de aprimorar minhas habilidades como desenvolvedor Fullstack.

Objetivos do Projeto
O principal objetivo deste projeto é colocar em prática os conceitos aprendidos durante o curso, abrangendo tanto o desenvolvimento Front-end quanto o Back-end. Ao trabalhar neste projeto, estarei melhorando minhas habilidades nas seguintes áreas:

HTML/CSS: Estrutura e estilização das páginas web.
Git & GitHub

Motivação
Este projeto faz parte de uma atividade curricular da faculdade e tem como foco principal o aperfeiçoamento das minhas habilidades práticas em desenvolvimento web, tanto no Front-end quanto no Back-end. É uma oportunidade para explorar o ciclo completo de desenvolvimento de uma aplicação web.

Próximos Passos
Melhorar a performance do código.
Implementar funcionalidades adicionais.
Refatorar o código para boas práticas de desenvolvimento.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Acessibilidade no Desenvolvimento Web
A acessibilidade é uma parte essencial do desenvolvimento web, pois garante que todos os usuários, independentemente de suas habilidades ou limitações, possam acessar e utilizar o site de maneira eficaz. No desenvolvimento entregue na Atividade 01 – Meu Primeiro Desenvolvimento WEB, algumas práticas e recursos de acessibilidade poderiam ser implementados para democratizar o acesso e melhorar a usabilidade do projeto para todos.

Características de Acessibilidade Implementáveis
1. Textos Alternativos para Imagens
Um dos princípios fundamentais da acessibilidade é garantir que as informações visuais estejam acessíveis para pessoas com deficiências visuais. Para isso, é importante utilizar o atributo alt nas imagens.

Recurso: Adicionar descrições textuais (alt) em todas as imagens para que leitores de tela possam descrever o conteúdo visual para os usuários que não podem vê-las.
Exemplo:
html
Copiar código
<img src="imagem.jpg" alt="Descrição clara da imagem">
2. Contraste Adequado entre Texto e Fundo
Usuários com baixa visão ou dificuldades em distinguir cores podem encontrar dificuldades em ler o conteúdo se o contraste entre o texto e o fundo for insuficiente.

Recurso: Garantir um alto contraste entre o texto e o fundo, utilizando ferramentas como o WebAIM Contrast Checker para verificar a conformidade com as diretrizes de acessibilidade.
Exemplo:
Texto escuro sobre fundo claro (#000 sobre #fff) ou texto claro sobre fundo escuro (#fff sobre #333).
3. Tamanho e Espaçamento Adequados do Texto
Pessoas com dificuldades de visão podem ter problemas para ler textos pequenos ou mal espaçados.

Recurso: Utilizar tamanhos de fonte adequados (mínimo de 16px) e ajustar o line-height para melhorar a legibilidade.
Exemplo:
css
Copiar código
body {
    font-size: 16px;
    line-height: 1.6;
}
4. Navegação por Teclado
Muitos usuários, incluindo aqueles com deficiências motoras, utilizam o teclado ao invés do mouse para navegar em um site.

Recurso: Certificar-se de que todos os elementos interativos (links, botões, formulários) são navegáveis pelo teclado utilizando a tecla Tab e que possuem foco visível.
Exemplo:
Verificar se os elementos possuem o atributo tabindex correto e estilos visíveis para o estado de foco.
css
Copiar código
a:focus, button:focus {
    outline: 2px solid #000;
}
5. Uso de ARIA (Accessible Rich Internet Applications)
Para melhorar a interação de pessoas que utilizam tecnologias assistivas, como leitores de tela, podemos adicionar atributos ARIA (Accessible Rich Internet Applications).

Recurso: Usar atributos ARIA como role, aria-label e aria-live para melhorar a navegação e descrever com clareza elementos interativos que, de outra forma, seriam inacessíveis ou confusos.
Exemplo:
html
Copiar código
<button aria-label="Fechar menu">X</button>
6. Formulários Acessíveis
Os formulários devem ser facilmente compreensíveis e navegáveis para usuários de tecnologias assistivas.

Recurso: Associar corretamente os rótulos (<label>) aos campos de formulário (<input>) para que os leitores de tela possam identificar e descrever os campos.
Exemplo:
html
Copiar código
<label for="nome">Nome:</label>
<input type="text" id="nome" name="nome">
7. Layout Responsivo
Usuários com limitações físicas ou visuais podem acessar o site em dispositivos móveis ou em telas com diferentes tamanhos.

Recurso: Implementar design responsivo para garantir que o site seja acessível e utilizável em todos os dispositivos e resoluções de tela.
Exemplo:
Uso de media queries para ajustar o layout em telas menores.
css
Copiar código
@media (max-width: 768px) {
    body {
        font-size: 14px;
    }
}
8. Legendas e Transcrições para Conteúdos Multimídia
Se o projeto incluir vídeos ou áudios, é essencial garantir que eles estejam acessíveis para pessoas com deficiência auditiva.

Recurso: Adicionar legendas para vídeos e transcrições para áudios, garantindo que o conteúdo esteja acessível para todos.
Exemplo: Usar a tag <track> para adicionar legendas a vídeos.
html
Copiar código
<video controls>
    <source src="video.mp4" type="video/mp4">
    <track src="legendas.vtt" kind="subtitles" srclang="pt-br" label="Português">
</video>
Conclusão
Ao implementar essas características de acessibilidade, o projeto desenvolvido na Atividade 01 poderia ser aprimorado significativamente, oferecendo uma experiência mais inclusiva para todos os usuários. A acessibilidade não apenas beneficia pessoas com deficiências, mas melhora a usabilidade geral do site, tornando-o mais funcional e fácil de usar para todos os visitantes.
