# Gizmo - from noobs for professionals


![Gizmo](https://www.mopop.org/media/2258/cla_artifacts_gizmo-0633_1200x630.jpg?anchor=center&mode=crop&width=1140&height=550&rnd=131826407410000000)

*Help me*

* This super program will allow you create project-name-based workspaces to help you control your workflow. This project is only for educational purposes only.

<hr>

### TODO
* Implement basic class sceletons
* Possibility to create workspaces, lists and cards
* Possibility to manage workspaces, lists and cards
* Assign roles to users connected to workspaces
* Moving cards between lists
* Change workspace background for free!
* Change cards priority
* If God will help us we will implement comments system foreach cards
<hr>

### Schedule
#### 13.04.2019
User will be able to:
* create account.
* create own workspace and select current.
#### 27.04.2019
User will be able to:
* create lists and cards
* assign roles to users connected to workspaces
* change card priority
* change workspace background for free!
#### 11.05.2019
User will be able to:
* move cards between lists
* edit components
* comment cards

## Installation

### Requirements
- java 8
- gradle
- mysql database
- redis database

### Instructions
1. Copy `src/main/resources/application-dev.properties.dist` to `src/main/resources/application-dev.properties` and fill or change required configuration
1. Start database servers configured in previous step
1. Start local `redis-server`
1. Start application server with `./gradlew bootRun` 

You can now go to [http://localhost:8080/](http://localhost:8080/). 

To gracefully shutdown server run `curl -X POST localhost:8080/actuator/shutdown`.  


*(image source: https://www.mopop.org/media/2258/cla_artifacts_gizmo-0633_1200x630.jpg?anchor=center&mode=crop&width=1140&height=550&rnd=131826407410000000)*
