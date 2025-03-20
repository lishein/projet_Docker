```bash
git clone "https://github.com/lishein/projet_Docker.git" && \
cd projet_Docker && \
git clone "https://github.com/lishein/Parking_API.git" api && \
git clone "https://github.com/lishein/Parking_FRONT.git" ui && \
docker compose up -d --build