<h1 align="center">Александр Вагнер</h1>

<p align="center">
  <b>Разработчик дата-платформы</b><br/>
  MCP-хаб · REST + MCP · ИИ-агенты в разработке
</p>

<p align="center">
  <img alt="role" src="https://img.shields.io/badge/role-data_platform_developer-blue?style=flat-square">
  <img alt="focus" src="https://img.shields.io/badge/focus-MCP_hub-2ea44f?style=flat-square">
  <img alt="protocol" src="https://img.shields.io/badge/protocol-REST_%2B_MCP-6f42c1?style=flat-square">
</p>

<p align="center"><img src ="https://github-readme-streak-stats.herokuapp.com?user=avagners&theme=darcula&hide_border=true&date_format=%5BY%20%5DM%20j&background=FFFFFF00" alt="streak stats"></p>

> Раньше данные были таблицами. Теперь данные — это интерфейс.

## Что я строю

Полтора года работаю над дата-платформой банка. До этого два года — инженером данных: ETL, хранилища, отчёты.

**Сейчас** — строю **MCP-хаб**, единую точку входа к сервисам платформы: посмотреть статусы DAG в Airflow, прочитать логи приложения в YARN, выполнить SQL-запрос через Trino. Люди и ИИ-агенты обращаются к платформе одинаково: один контракт, один слой авторизации, одна документация.

```mermaid
flowchart LR
    U["Пользователь"] -->|REST| HUB["MCP-хаб"]
    A["ИИ-агент"] -->|MCP| HUB
    HUB --> AF["Airflow<br/>статусы DAG"]
    HUB --> YN["YARN<br/>логи приложений"]
    HUB --> TR["Trino<br/>SQL-запросы"]
```

## Как работаю

Индустрия укрупняет роли: аналитик, разработчик, тестировщик и дежурный схлопываются в одного **продуктового инженера**, а команды сжимаются до tiny teams. Укрупнение стало возможным благодаря ИИ: границы между соседними областями перестали быть барьером — задачу из чужой зоны можно подхватить, а не ждать освободившегося специалиста. Я работаю в этой парадигме последние годы.

В моей команде три разработчика, и на троих — весь цикл: разобраться в задаче, спроектировать контракт, написать код, покрыть тестами, выкатить и ответить, если ночью что-то упало.

## Стек

<p align="left">
    <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
    <a href="https://www.microsoft.com/en-us/sql-server/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/microsoftsqlserver/microsoftsqlserver-plain-wordmark.svg" alt="ms sql server" width="40" height="40"/> </a>
    <a href="https://airflow.apache.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apacheairflow/apacheairflow-original.svg" alt="airflow" width="40" height="40"/> </a>
    <a href="https://spark.apache.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachespark/apachespark-original.svg" alt="spark" width="40" height="40"/> </a>
    <a href="https://hadoop.apache.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/hadoop/hadoop-original.svg" alt="hadoop" width="40" height="40"/> </a>
    <a href="https://trino.io/" target="_blank"> <img src="https://img.shields.io/badge/Trino-SQL-6f42c1?style=flat-square&logo=trino&logoColor=white" alt="trino" height="28"/> </a>
    <a href="https://www.docker.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-plain.svg" alt="docker" width="40" height="40"/> </a>
    <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
    <a href="https://www.gnu.org/software/bash/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a>
    <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a>
</p>

<p align="center"><sub>профиль, который давно притворяется сервисом</sub></p>
