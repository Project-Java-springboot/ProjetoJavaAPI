youtube-downloader/ 
├── HELP.md                             # Documentação do projeto
├── mvnw                                # Wrapper Maven (para rodar o Maven sem precisar ter o Maven instalado)
├── mvnw.cmd                            # Wrapper Maven para Windows
├── pom.xml                              # Arquivo de configuração do Maven
└── src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── br/
│   │           └── youtubedownloader/
│   │               └── youtube_downloader/
│   │                   ├── App.java           # Ponto de entrada do Spring Boot
│   │                   ├── downloader/
│   │                   │   └── VideoDownloader.java  # Lógica de download
│   │                   ├── ui/
│   │                   │   └── CLI.java       # Interface de linha de comando
│   │                   └── utils/
│   │                       └── Validator.java # Validação do link do YouTube
│   └── resources/
│       ├── application.properties   # Configurações do Spring Boot
│       ├── static/                  # Arquivos estáticos (se necessários)
│       └── templates/               # Templates (se necessários)
└── test/
└── java/
└── com/
└── br/
└── youtubedownloader/
└── youtube_downloader/
├── AppTest.java          # Testes para o ponto de entrada
├── CLITest.java         # Testes para a interface CLI
├── ValidatorTest.java   # Testes para a validação de links
└── VideoDownloaderTest.java # Testes para a lógica de download
