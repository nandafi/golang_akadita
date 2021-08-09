//Library


+Referency github : https://github.com/ydhnwb/golang_api

#http framework
    go get -u github.com/gin-gonic/gin
#env - untuk bikin environment
    go get github.com/joho/godotenv/cmd/godotenv
#database
    go get -u gorm.io/gorm
#mysql-driver
    gorm.io/driver/mysql
	"github.com/ydhnwb/golang_api/helper"
	"github.com/ydhnwb/golang_api/service"   
    golang.org/x/crypto/bcrypt 
    go get github.com/mashingan/smapping
---------------------------------------------

{https://www.youtube.com/watch?v=zUMUbmB6krA&list=PLkVx132FdJZlTc_1gucKZ00b_s45DQlVQ&index=2}
1. create db "golang_api"
2. create folder "config"
3. create file "database-config.go"

#3 Golang RESTful API MySQL + Gin + Gorm + JWT - Entity
https://www.youtube.com/watch?v=yGTMQ5e-T5E&list=PLkVx132FdJZlTc_1gucKZ00b_s45DQlVQ&index=3
1. Create folder "entity"
2. Create file /book.go, user.go


#5 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - Preparing AuthController
https://www.youtube.com/watch?v=9tp82wyG-Mc&list=PLkVx132FdJZlTc_1gucKZ00b_s45DQlVQ&index=5
1. Create folder "controller" --> create file "auth-controller.go"
2. test handler, login & register

#6 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - Data Transfer Object
1. create folder "dto"
    - book-dto.go
    - user-dto.go
    - login-dto.go
    - register-dto.go


#7 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - JWTService
    1. Create folder "service" --> jwt-service.go

#8 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - JWT Auth Midlleware
    1. Create folder "middleware" --> jwt-auth.go

#9 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - User Repository
1. create folder "repository" --> user-repository.go

#10 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - Auth Service
1. folder "repository"  --> user-repository.go
2. fodler "service"     --> auth-service.go
----------------------------------------------------------------------------------------- 5 Agustus 2021


--------------------------------
6 Agustus
--------------------------------
#12 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - Testing Login & Register Feature
1. update server.go & test POST : login,register

#13 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - User Service
1. folder :
    service/user-service.go
    controller/user-controller.go
2. Edit server.go : nambah terkait userService

#14 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - Testing User Module
1. Testing user/profile, user/update

#15 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - Book Repository
1. Create repository/book-repository.go
2. Create service/book-service.go

#17 Golang RESTful API Dengan MySQL + Gin + Gorm + JWT - Book Controller
1. Create controller/book-controller.go