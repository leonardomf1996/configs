# configs

Configurações pessoais, pode sofrer alterações 



    // Tema do VS Code
    "workbench.colorTheme": "Dracula",

    // Tamanho da fonte no terminal
    "terminal.integrated.fontSize": 14,
    
    // Tema dos icones no sidebar
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",
    
    // Configura o tamanho e família da fonte
    "editor.tabSize": 3,
    "editor.fontSize": 14,
    "editor.lineHeight": 20, 
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "editor.formatOnPaste": true,
    "editor.formatOnType": true,
    "formattingToggle.affects": ["formatOnSave"],
    
    // Quando cria uma pasta dentro de outra pasta vazia
    "explorer.compactFolders": false,
    
    // Mostrar qual linha está selecionada, mas apenas na esquerda, no nº
    "editor.renderLineHighlight": "gutter",
    
    // Informar na aba do arquivo em qual pasta o arquivo está
    "workbench.editor.labelFormat": "short",
    
    // Ignorar recomendações do editor para extensões
    "extensions.ignoreRecommendations": true,
    
    // Oara qyabdi niver arquivos .js ou .ts, eu mesmo alterar importações e não o editor, pois pode ocorrer erros
    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.updateImportsOnFileMove.enabled": "never",
    
    // Mostrar o caminho completo do arquivo que você está (fica abaixo das abas)
    "breadcrumbs.enabled": true,
    
    // Para o editor não ficar mostrando dicas de parâmetros
    "editor.parameterHints.enabled": false,
    
    // Para o editor não ficar perguntando se você quer mesmo deletar o arquivo ou movê-lo
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    
    // Para sugerir auto complete
    "emmet.syntaxProfiles": {
        "javascript": "jsx"
    },
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "editor.rulers": [
        80,
        120
    ],
    
    // Para que o EsLint corrija meu código após salvar para os seguintes formatos
    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "material-icon-theme.folders.associations": {
        "infra": "app",
        "entities": "class",
        "schemas": "class",
        "typeorm": "database",
        "repositories": "mappings",
        "http": "container",
        "migrations": "tools",
        "modules": "components",
        "implementations": "core",
        "dtos": "typescript",
        "fakes": "mock",
    },
    "material-icon-theme.files.associations": {
        "ormconfig.json": "database",
        "tsconfig.json": "tune"
    },
    "diffEditor.ignoreTrimWhitespace": false,
    "bracketPairColorizer.depreciation-notice": false

