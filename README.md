## 公式ドキュメント
https://docs.docker.com/compose/rails/


## RUN

+ git clone https://github.com/oshimamasara/docker-rails-mac-Linux.git
+ cd docker-rails-mac-Linux
+ docker-compose run web rails new . --force --no-deps --database=postgresql
+ docker-compose build
+ Edit config/database.yml
+ docker-compose run web rake db:create
+ docker-compose up   or    docker-compose up -d

check  localhost:3000

+ [YouTube Ubuntu](https://youtu.be/cGJUJ2FiAz4)
+ [YouTube Mac](https://youtu.be/M9vIBIoPznE)
