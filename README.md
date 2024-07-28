![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
# Desafio da fase 02
## Intermediário - Semântica e acessibilidade. 💜
### Sobre o desafio

Sabemos que a maior parte do conteúdo disponível na internet hoje pode se tornar acessível apenas com a utilização correta dos elementos do HTML.

Você receberá um código com o projeto desenvolvido durante a Fase 02, mas, ao contrário do que foi feito em aula, ele não apresenta a semântica correta.
Como você pode ver na imagem abaixo, a página continua funcionando normalmente mas, quando você abrir o código, vai se deparar com os elementos do HTML todos bagunçados... 👀

#### Site sem semântica:
<img src="./github/site-sem-semantica.png" alt="Site sem semântica">

Topa encarar esse desafio e deixar o site mais acessível? 💜
Vai ser muito importante para o seu aprendizado rever e aplicar esses novos conceitos. 

<u>Lembrando:</u> tente se desafiar e não olhar a resposta mas, caso apareça alguma dificuldade, você pode voltar nas aulas e rever a maneira com que foi desenvolvido!

### Desafio concluído
Código foi arrumado de maneira que o site ficasse com uma melhor semâtica e sem modificar a aparência do mesmo, mantendo-o igual ao que está apresentado no [Figma](https://www.figma.com/file/rkDOHGPwwFtBNqEdHSuQPd/Projeto-02---Explorer?node-id=0%3A1).

#### O que foi corrigido? 🧐
- Remoção das tags `div` sem justificativa. As tags `div` são tags genéricas e por isso não trazem nenhuma semântica, logo elas foram trocadas por outras tags que trazem uma melhor semântica sem prejudicar a estilização do site. Vale lembrar que a tag `div` com a classe `page` foi mantida porque o uso dela é justificada pelo CSS e a sua remoção altera a estilização do site.
- Inclusão de atributos `ARIA` ***(Accessible Rich Internet Applications)*** pois melhoram a acessibilidade para tecnologias assistivas.
- Foram Adicionadas/revisadas as descrições das imagens para que ficassem mais detalhadas, garantindo que usuários com deficiências visuais possam entender o conteúdo das imagens.
