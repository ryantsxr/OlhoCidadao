# Olho Cidadão — MVC

Projeto reorganizado no padrão **MVC (Model, View, Controller)** em PHP.

## Estrutura

- `app/Controllers/` — regras de controle e fluxo das páginas
- `app/Models/` — acesso e manipulação dos dados
- `app/Views/` — HTML das telas
- `app/Core/` — classes base e roteador
- `public/` — ponto de entrada, CSS, JavaScript, imagens e uploads
- `storage/` — arquivos JSON usados como armazenamento

## Como executar no XAMPP/Apache

1. Mantenha a pasta `OlhoCidadao_MVC` dentro de `htdocs/OlhoCidadao`.
2. Confirme que o Apache está ligado.
3. Acesse:

   `http://localhost/OlhoCidadao/OlhoCidadao_MVC/`

O `.htaccess` da raiz já encaminha as requisições para `public/index.php` e os arquivos estáticos para `public/`.

## Importante

Não é necessário acessar diretamente `public/index.php`. O projeto pode ser acessado pela pasta raiz.

O sistema também pode ser executado com o servidor embutido do PHP:

```bash
php -S localhost:8000 -t public
```

Nesse caso, acesse `http://localhost:8000/`.
