This is a Dockerized [Next.js](https://nextjs.org/) project.

## Getting Started


1. Copy **Dockerfile** and **docker-compose.yml** to your project
2. change **next.config.js** and add this code end of **nextConfig** 
```bash
 experimental: {
    outputStandalone: true,
  }
```



## Run

#### 1.Build Docker Image

```bash
  docker build . -t project
```

#### 2.Run With Docker Compose
```bash
  docker-compose up
```
or
```bash
  docker-compose up -d
```

## Authors

- [Vercel/Next.js](https://github.com/vercel/next.js/)
- [Vahid Rezazadeh](https://github.com/vahidrezazadeh)


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](http://vahidrezazadeh.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vahidrezazadeh)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/vahidrezazadeh5)

