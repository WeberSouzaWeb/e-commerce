# e-commerce

## frontend <a href="https://vite.dev/"><img src="https://vitejs.dev/logo.svg" width="25"></img></a>
O [Vite](https://vite.dev/) é uma ferramenta de desenvolvimento web que otmiza produção e modulos.

Para rodar a aplicação, você deve ter o Vite [create-vite](https://github.com/vitejs/vite/tree/main/packages/create-vite), e então basta rodar o comando para sua construção. No meu caso o comando é `npm create vite@latest`, por ser construido com Node.js. O comando deve ser rodado na pasta raíz do projeto, onde o frontend será desenvolvido.
    
    Project name: frontend
    Select a framework: React
    Select a variant: JavaScript
    cd frontend
    npm install 
    npm run dev

![image](https://github.com/user-attachments/assets/cd4b4157-9b25-440f-a0b6-fc16c46f80a3)


## backend | <a href="https://nodejs.org/"><img src="https://nodejs.org/static/logos/nodejsLight.svg" width="80"></img></a> 
 Para o backend, utilizei o Node.js
 
 ### Instalations
 
    npm install express
    npm install jsonwebtoken
    npm install mongoose
    npm install multer
    npm install cors
    
 ### Collections
 A collection principal é a `Product`, definida como no exemplo abaixo:
 ```
{
    id: 1,
    name: "Striped Flutter Sleeve Overlap Collar Peplum Hem Blouse",
    category: "women",
    image: p1_img,
    new_price: 50.0,
    old_price: 80.5,
}
```


 ### Data Base | <a href="https://www.mongodb.com/"><img src="https://webimages.mongodb.com/_com_assets/cms/kuyjf3vea2hg34taa-horizontal_default_slate_blue.svg" width="85"></img></a>

    
                      
## admin
[![image](https://vitejs.dev/logo.svg)](https://vitejs.dev/)

    npm create vite@latest .
    npm install
    npm run dev
    npm install react-router-dom
