# Finance FastAPI


## Brief Info.
- swagger page url: `http://<url>/documentation`


## RUN 

**Release**
```bash
docker compose --profile prod up -d --build
```
**Dev env. setup**
```bash
docker compose --profile dev up -d --build
```

## Pre-requirements
To use open DART (Korea) you need to issue key -> 
[how to open dart api key issue (korean)](https://coding-moomin.tistory.com/5)

## TODO
- [ ] dart finance statement crawling
- [ ] apply `pipenv` for requirements auto updates
- [v] connect to kakao API
