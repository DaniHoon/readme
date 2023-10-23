![logo](https://static.wanted.co.kr/images/events/3178/58ac3248.jpg)

# 메일 정리 자동화 웹서비스
고객의 메세지를 태그, 스팸 처리 등 자동으로 분류해주는 웹 서비스

<br/>

## Table of Contents
- [개요](#개요)
- [Skils](#skils)
- [Installation](#Installation)
- [Running Tests](#running-tests)
- [API Reference](#api-reference)
- [TIL 및 회고](#til-및-회고)
- [Authors](#authors)
- [References](#references)

<br/>


## 개요
이 서비스가 어떠한 배경에서 발견한 문제상황을 해결하기 위해 시작되었는지 및 어떠한 방법으로 해당 문제를 해결하려 하는지 등 ... To use a badge:
- Via Github
    1. Press `Ctrl` + `f` on your keyboard, to bring out the search modal.
    1. Enter the name of the badge you need.
    1. Copy the appropriate `![Name](link)` element and paste it in your Markdown file (e.g. README.md)
- You could also visit the live site at [ileriayo.github.io/markdown-badges/](https://ileriayo.github.io/markdown-badges/)


## Skils
가상환경: ![Static Badge](https://img.shields.io/badge/Conda-green)<br/>언어 및 프레임워크: ![Static Badge](https://img.shields.io/badge/Python-3.10-blue) ![Static Badge](https://img.shields.io/badge/Django-REST-red)<br/>
데이터 베이스: ![Static Badge](https://img.shields.io/badge/Postgresql-9.2.4-blue) <br/>
배포 : ![Static Badge](https://img.shields.io/badge/Docker-039BC6) ![Static Badge](https://img.shields.io/badge/AWS-EC2-orange) ![Static Badge](https://img.shields.io/badge/Github-Actions-black)  <br/> ETC : ![Static Badge](https://img.shields.io/badge/Celery-black) ![Static Badge](https://img.shields.io/badge/Redis-red)


## Installation

Install my-project with npm

```bash
  # Package 설치
  npm install my-project
  cd my-project
  
  # 초기 설정 : 데이터 및  스케쥴러 실행
  npm install my-project
  cd my-project
```
    
    
## Running Tests

To run tests, run the following command

```bash
  npm run test
```

> Coverage ScreenShot ![Static Badge](https://img.shields.io/badge/Test_Passed-20/20-green)
![coverage](https://user-images.githubusercontent.com/48683566/56673924-0b84ae00-66b1-11e9-93ac-fb76ff96a5a0.png)


## API Reference

<details>
<summary>Get all items - click</summary>

#### Request
```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Response
```http
    HTTP/1.1 200
    Content-Type: application/json

    [{
        "id": 10,
        "name": "shirt",
        "color": "red",
        "price": "$23"
    },...
    ]
```
</details>
<details>
<summary>Get all items - click</summary>

#### Request
```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Response
```http
    HTTP/1.1 200
    Content-Type: application/json

    [{
        "id": 10,
        "name": "shirt",
        "color": "red",
        "price": "$23"
    },...
    ]
```
</details>
<details>
<summary>Get all items - click</summary>

#### Request
```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Response
```http
    HTTP/1.1 200
    Content-Type: application/json

    [{
        "id": 10,
        "name": "shirt",
        "color": "red",
        "price": "$23"
    },...
    ]
```
</details>
    
## TIL 및 회고

<details>
<summary>Django ORM 조회 시 발생하는 00 버그 - click</summary>
- 의존성 문제
    1. Press `Ctrl` + `f` on your keyboard, to bring out the search modal.
    2. Enter the name of the badge you need.
    3. Copy the appropriate `![Name](link)` element and paste it in your Markdown file (e.g. README.md)
- 00가 00 하는 문제
</details>
<details>
<summary>Django ORM 조회 시 발생하는 00 버그 - click</summary>
- 의존성 문제
    1. Press `Ctrl` + `f` on your keyboard, to bring out the search modal.
    2. Enter the name of the badge you need.
    3. Copy the appropriate `![Name](link)` element and paste it in your Markdown file (e.g. README.md)
- 00가 00 하는 문제
</details>

## Authors

- [@octokatherine](https://www.github.com/octokatherine)
- [@octokatherine](https://www.github.com/octokatherine)
- [@octokatherine](https://www.github.com/octokatherine)



## References

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)



