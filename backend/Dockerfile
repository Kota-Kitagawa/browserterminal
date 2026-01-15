FROM oven/bun:latest
WORKDIR /app
COPY . .
RUN bun install
RUN apt-get update && apt-get install -y  vim
EXPOSE 3000
CMD ["bun", "run", "src/index.ts"]