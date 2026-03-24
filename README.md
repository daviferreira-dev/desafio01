🐾 Express - E-commerce de Alta Conversão

Este projeto foi desenvolvido como parte do 1º desafio da disciplina de Front-End no SENAI Taubaté. O objetivo foi realizar o refactoring de uma estrutura base, transformando-a numa solução de e-commerce moderna, performática e focada na experiência do utilizador (UX).

🚀 Tecnologias Utilizadas
HTML5: Estrutura semântica focada em SEO e acessibilidade.

CSS3 (Moderno): Utilização de variáveis globais (:root), Flexbox e Grid para um layout responsivo e de fácil manutenção.

JavaScript (ES6+): Lógica de interatividade, manipulação dinâmica do DOM e gatilhos mentais.

Intersection Observer API: Implementada para gerir animações de scroll de forma performática.

Firebase: Utilizado para a estruturação e hosting da aplicação.

🛠️ Diferenciais Técnicos
1. Performance com Intersection Observer
Ao contrário dos eventos de scroll tradicionais que podem sobrecarregar o browser, utilizei a Intersection Observer API. Esta deteta de forma assíncrona quando os elementos (vantagens e reviews) entram na área de visualização, disparando as animações apenas quando necessário.

2. Gatilhos de Conversão (Social Proof)
Implementei uma lógica em JavaScript que gera dados dinâmicos de estoque e visualizações simultâneas.

Estoque Dinâmico: Gera um senso de urgência.

Viewers em Tempo Real: Cria prova social, simulando um ambiente de alta demanda.

3. Arquitetura CSS Escalável
O projeto utiliza um sistema de Variáveis CSS para cores e transições. Isto permite que a identidade visual da marca seja alterada em segundos, modificando apenas o :root, seguindo as melhores práticas de Clean Code.

4. UX e Interatividade
Galeria Dinâmica: Troca instantânea de imagens de produto.

Zoom Interativo: Efeito de escala no produto principal para visualização de detalhes técnicos.

Feedback Visual: Botão de compra com alteração de estado e cor após o clique.

📦 Como rodar o projeto
Clona este repositório:

Bash
git clone https://github.com/daviferreira-dev/desafio01.git
Navega até a pasta do projeto:

Bash
cd desafio01
Abre o ficheiro produtoPet.html no teu navegador ou utiliza a extensão Live Server do VS Code.

👥 Membros do Grupo
Davi Ferreira da Cunha

Guilherme Emanuel Gonçalves

Cassiano Luiz Brandes Soares

Rodrigo Santos Graça

Este projeto foi desenvolvido com fins educativos sob a orientação do Prof. Marcelo Benevides.

