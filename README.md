# QuickPic

## PROJETO LOCAL

/meu-projeto  
│  
├── /frontend  
│   ├── index.html          # Página de login  
│   ├── dashboard.html      # Página principal com upload de fotos  
│   ├── styles.css          # Arquivo de estilos  
│   └── app.js              # Lógica de front-end  
│  
├── /backend  
│   ├── server.js           # Servidor Express  
│   ├── auth.js             # Funções de autenticação (login, registro)  
│   ├── middleware.js       # Middleware para proteger rotas  
│   ├── uploadPhoto.js      # Função para upload de fotos (simulando Lambda)  
│   ├── deletePhoto.js      # Função para exclusão de fotos (simulando Lambda)  
│   └── listPhotos.js       # Função para listar fotos (simulando Lambda)  
│  
├── /data                   # Armazenamento local simulado  
│   └── /photos             # Pasta para armazenar fotos temporariamente  
│  
├── /uploads                # Pasta para armazenar uploads temporários  
│  
├── package.json            # Dependências e scripts do Node.js  
└── README.md               # Documentação do projeto  

  

## PROJETO AWS  

/meu-projeto  
│  
├── /frontend  
│   ├── index.html        # Página de login  
│   ├── dashboard.html    # Página principal com upload de fotos  
│   └── styles.css        # Arquivo de estilos  
│  
├── /lambda  
│   ├── auth.js             # Funções de autenticação (login, registro)  
│   ├── uploadPhoto.js    # Função Lambda para upload de fotos  
│   ├── uploadPhoto.js    # Função Lambda para upload de fotos  
│   ├── deletePhoto.js    # Função Lambda para exclusão de fotos expiradas  
│   └── listPhotos.js     # Função Lambda para listar fotos disponíveis  
│  
├── /scripts  
│   └── deploy.js         # Script para deploy usando AWS CLI ou SDK  
│  
├── package.json          # Dependências e scripts do Node.js  
├── .env                  # Variáveis de ambiente para conexão com AWS  
└── README.md             # Documentação do projeto  
