# Cyber Security

## Information
- Siriprapha Sombatkham (wawa)
- 6602041610020
- s6602041610020@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running a services
### Database
```sh
docker compose -f db.yaml up # nonitoring
docker compose -f db.yaml up -d # backaround
```

### Admin
```sh
docker compose -f admin.yaml up # nonitoring
docker compose -f admin.yaml up -d # backaround
```