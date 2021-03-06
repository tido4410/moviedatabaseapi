[![codebeat badge](https://codebeat.co/badges/07eeaf3d-d079-4f7f-8ba5-abf596b60f31)](https://codebeat.co/projects/github-com-gabrielbmoro-moviedbapi-master)

# Welcome!

- This repository provides an Android project that uses the library  [Movie DB API](https://www.themoviedb.org)

## Architecture

![Architecture](https://github.com/gabrielbmoro/MovieDBApi/blob/master/img/architecture.svg)

## Coverage 

> _Last update 12/08/20_

| Layer                | Coverage (% classes)      |
|----------------------|:-------------------------:|
| core                 | _58%_                     |
| domain               | _93%_                     |
| presentation         | _15%_                     |
| repository           | _64%_                     |

Total: _44%_



## Stack Overview

| Type                 | Current Implementation  |
|----------------------|:-----------------------:|
| Architecture         | MVVM                    |
| Dependency Injection | Koin                    |
| Load Images          | Glide                   |
| View Binding         | Kotlin Synthatics       |
| Handler to IO calls  | Coroutines              |
| Unit Tests           | JUnit, Truth, mockK     |
| UI Tests             | Espresso, Truth         |
| Network calls        | Retrofit                |
| Json converter       | Retrofit - Gson         |
| Persistence          | Room and Paging 2       |

## Teaser

![Android Native Version](https://github.com/tido4410/moviedatabaseapi/blob/master/img/teaser.gif)

- Night mode: https://github.com/tido4410/moviedatabaseapi/blob/master/img/dark-theme-support.gif
