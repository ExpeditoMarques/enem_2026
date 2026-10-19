# Planner de Estudos ENEM 2026

Planner responsivo em português para acompanhar o cronograma de estudos de 19/10 a 15/11/2026.

## Recursos
- Cronograma diário com tarefas marcáveis.
- Filtros para pendentes, concluídas, redação e questões/simulados.
- Indicador de progresso e contagem de redações.
- Backup JSON para exportar/importar marcações.
- Layout responsivo para celular e computador.
- Cache básico para abrir o app offline depois do primeiro acesso.

## Publicar com GitHub Pages
1. Abra **Settings** neste repositório.
2. Entre em **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch **main** e a pasta **/ (root)**; clique em **Save**.
5. Aguarde o GitHub publicar e abra o endereço que aparecer na tela do Pages.

## Importante sobre o progresso
As marcações são guardadas no armazenamento local do navegador (localStorage). Isso funciona sem conta e sem servidor, mas **não sincroniza automaticamente entre dispositivos ou navegadores**. Para usar outro aparelho, exporte o backup JSON no dispositivo antigo e importe-o no novo.

## Arquivos
- `index.html`: interface, cronograma e lógica do planner.
- `manifest.json`: metadados para instalação compatível.
- `sw.js`: cache para acesso offline após o primeiro carregamento.

## Observação sobre as datas
O cronograma foi montado a partir do plano solicitado nesta conversa. Confira datas, local e cartão de confirmação nos canais oficiais do ENEM antes da prova.
