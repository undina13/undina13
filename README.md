<a href="https://t.me/undina_13">
  <img align="left" alt="Telegram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/telegram.svg" />
</a>


## Мои проекты


🎭 **Explore With Me** — приложение, которое дает возможность делиться информацией об интересных событиях и помогает найти компанию для участия в них. Микросервисная архитектура с использованием Spring Boot, Hibernate, PostgreSQL и Docker.<br/>
https://github.com/undina13/java-explore-with-me

🎥 **Filmorate** - REST-сервис с использованием Spring Boot, Maven, Lombok и взаимодействие с БД  с помощью JDBC: Кинопоиск для своих - социальная сеть, которая
поможет выбрать кино на основе того, какие фильмы вы и ваши друзья смотрите и какие оценки им ставите.<br />
https://github.com/undina13/java-filmorate-1

📙 **Advertesment** - Реализация приложения доски объявлений с реализацией регистрации и аутентификации пользователей. REST-сервис с использованием Spring Security, Spring Boot, Maven, Lombok, Swagger, Postgres, Docker<br />
https://github.com/undina13/backendServer

🎮 **ShareIt** - REST-сервисы с использованием Spring MVC, SpringData, Hibernate, PostgreSQL, Docker Compose. 
Приложение для обмена вещами среди друзей на время: инструментами, гаджетами, книгами, играми. Как каршеринг, только для вещей.<br />
https://github.com/undina13/java-shareit

💾 **Disk** бэкенд для веб-сервиса хранения файлов, аналогичный сервису Яндекс Диск. Пользователь загружает и структурирует файлы в предложенном ему облачном пространстве. Пользователь может скачивать файлы и фиксировать историю их изменений. REST-сервисы с использованием Spring MVC, SpringData, Hibernate, PostgreSQL, Docker Compose. <br />
https://github.com/undina13/enrollment


- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{undina_13}}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
