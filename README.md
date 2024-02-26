## Laravel Devcontainer Example

- `CTRL+SHIFT+P` seleziona `Dev Containers: Rebuild and Reopen in Container`
- `CTRL+ò` per aprire un terminale
  - installiamo le dipendenze `composer install`
  - copia il file env con `cp .env.example .env`
  - generiamo la chiave dell'applicazione `php artisan key:generate`

### Auth - Breeze (Vue with Inertia)

- `CTRL+ò` per aprire un terminale
  - aggiungiamo la libreria laravel/breeze `composer require laravel/breeze --dev`
  - la configuriamo con `php artisan breeze:install`
  - aggiorniamo il db `php artisan migrate`