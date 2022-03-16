# aprendendo-sobre-objetos-JS
Este é um conteúdo sobre objetos em javascript onde estou ainda na parte básica.



const pet1 = {
    tipo: 'cachorro',
    nome: 'Théo',
    raça: 'Shitzu',
    idade: '2 anos',
    fala(){
        console.log(`O ${this.tipo} de nome ${this.nome} e de raça ${this.raça} tem ${this.idade} de idade.`);
    }
};

    const pet2 = {
        tipo: 'gato',
        nome: 'Miau',
        raça: 'cianês',
        idade: '5 anos',

    fala(){
        console.log(`O ${this.tipo} de nome ${this.nome} e de raça ${this.raça} tem ${this.idade} de idade.`);
    }
    
};
 pet1.fala();
 pet2.fala();
