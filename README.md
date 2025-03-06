# DSTI lab 10 - Authentication

## Install

- Clone this repo:
```bash
git clone https://github.com/EliottElek/dsti-lab-10-authentication.git
  ```
- Copy `.env` files:
```bash
cd dsti-lab-10-authentication
cp ./supabase/.env.example ./supabase/.env && cp ./next-client/.env.example ./next-client/.env.local
```
- Run the project:
```bash
docker compose -f ./supabase/docker-compose.yml -f ./next-client/docker-compose.yml up -d
  ```

Now: 

- Supabase client should be available at: [http://localhost:8000](http://localhost:8000)
- Web client should be available at: [http://localhost:3000](http://localhost:8000)
