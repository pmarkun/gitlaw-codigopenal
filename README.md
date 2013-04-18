# Reforma do Código Penal

Esse projeto tem por objetivo sistematizar as contribuições do grupo Transparência Hacker sobre a reforma do código penal.

Mais específicamente, mas não restrito, aos cápitulos que falam sobre crimes cibernéticos e crimes contra a propriedade intelectual.

## Git?

Já fizemos mutirões em diferentes plataformas como [Google Docs](http://docs.google.com), [CrocoDocs](http://crocodocs.com) e [Pads](http://okfnpad.org/).

Para esse mutirão gostariamos de experimentar o uso do git - um sistema criado para desenvolvimento de códigos computacionais de maneira distribuida.

O git tem uma curva de aprendizado um pouco mais complexa que as outras ferramentas - mas tem um grau muito maior de controle que permite a gente entender depois de onde vieram e que fim levou sugestões individuais.

## Como colaborar

* Acesse [http://github.com](https://github.com/)
* Crie sua conta com nome de usuário, email e senha
* Faça login!

* Navegue para o repositório: [https://github.com/pmarkun/gitlaw-codigopenal](https://github.com/pmarkun/gitlaw-codigopenal)

Esse é o repositório master. É aqui que vamos concentrar as alterações finais no documento.

Existem três coisas básicas para fazer por aqui:

* Observar o repositório.
* Adicionar uma questão (issue).
* Forkar o repositório.

### Observar o repositório

Clicando em 'Watch' você vai passar a observar esse repositório e ser notificado pelo github das discussões que estiverem acontecendo.

No settings você pode configurar que tipo de alertas quer receber e como.

### Adicionar uma questão (Issue)

O Issue Tracker é uma das ferramentas mais legais do github. Clicando em Issues -> New Issue você pode adicionar novas questões sobre o código. Sejam elas 'questions' - questões gerais sem necessariamente uma correção específica,'bugs' - problemas encontrados no código atualmente, ou 'enhacement' que são partes novas de código que precisam ser escritas para resolver questões que ainda não tinham sido pensadas.

O Github fez um [post de blog](https://github.com/blog/831-issues-2-0-the-next-generation) falando sobre o Issues.

**Importante** o github não tem uma forma fácil de relacionar um Issue com um trecho específico do código. Sempre que esse for o caso (e a sua questão tiver algo a ver com um ou mais ártigos específicos) lembre de relacionar eles no corpo da questão.

E também lembre de checar o Issues para ver se já não tem uma outra questão discutindo o mesmo assunto e se junte aquela discussão ao invés de criar uma nova.

### Forkar o repositório

Como falamos, o git é uma ferramenta para edição distribuida de código - ao contrário do Google Docs ou do Pad onde todos trabalham na mesma versão ao mesmo tempo, o git permite que centenas de pessoas trabalhem cada uma na sua versão e vai atualizando e combinando os documentos aos poucos.

A vantagem desse modelo é que em um contexto como o das leis onde podemos ter uma série de sugestões parecidas não precisamos adotar necessariamente 'a última versão' e podemos ter uma visualização melhor de como as mudanças se encadeiam.

Para colaborar com o documento o primeiro passo é fazer um **fork**. Com isso o github vai fazer uma cópia identica (e contectada) do documento para a sua conta.

Clique em **fork** e veja a mágica acontecer!

### Trabalhando no seu fork

Agora você esta no seu fork. Aqui você pode mexer a vontade sem medo de que isso vá gerar algum problema ou atrapalhar o trabalho de outra pessoa :)

Temos agora que copiar o repositório para o seu computador, para que você possa trabalhar offline no documento.

Se você ainda não instalou o git - siga um desses tutoriais:

* [Windows](http://windows.github.com/)
* [Mac](http://mac.github.com/)
* [Ubuntu](https://www.digitalocean.com/community/articles/how-to-install-git-on-ubuntu-12-04)

O resto desse documento vai partir do principio que você vai usar git via linha de comando. Mas com alguma sorte você consegue seguir ele usando um cliente gráfico também.

Com o git instalado e configurado, você vai clonar o repositório para a sua maquina para poder trabalhar.

No Terminal navegue para a pasta onde você quer que fique guardado os seus repositórios:

	git clone git@github.com:usuario/gitlaw-codigopenal.git

Quando você forkar o repositório o git vai te dar esse comando de lambuja. Aproveite e faça um ctrl+c / ctrl+shift+v (no terminal você precisa do shift para colar e copiar coisas)

Feito! Agora o arquivo `anteprojeto.md`, esse arquivo que você esta lendo e a pasta `/raw` contendo o original em PDF devem estar copiados felizes no seu computador.

Com o arquivo na sua maquina é hora de começar as modificações. O git ciclo do git é assim ó:

* Verifica se tem modificações: git pull
* Modifica o(s) arquivo(s)
* Adiciona as modificações no stage: git add nomedoarquivo
* Salva (commita) as modificações no repositorio: git commit -m 'comentario sobre as modificações feitas)
* Envia as modificações pro repositório online: git push
* Repete o primeiro passo :)

Existe ainda um último passo que é enviar as modificações que você fez no seu fork para o repositório final. Que é chamado de `Pull Request`.

Para isso, na interface web, quando você estiver feliz com suas modificações e sugestões clique no botão **Pull Request** e o github vai te guiar pelo processo.
