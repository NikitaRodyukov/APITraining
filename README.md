# APITraining
1. Регистрация

Тело запроса: 
{"user":{
    	"username": "NikitaRodyukove",
    	"email": "nikitarodwork@gmail.com",
    	"password": "thisispassword123"
  	}
}

Ответ с сервера:
{"user":{
	"username":"nikitarodyukove",
	"email":"nikitarodwork@gmail.com",
	"token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMGUzMDg4M2NmNzA1MWIwMDgyOWYzMyIsInVzZXJuYW1lIjoibmlraXRhcm9keXVrb3ZlIiwiZXhwIjoxNjY3MDU4MzEyLCJpYXQiOjE2NjE4NzQzMTJ9.mcGoZw4-RwidbgXEIq5hnBmudF-SKH3Q4PzO_aH8a9Y"
	}
}

2.Авторизация 

Тело запроса: 
{"user":{
    	"email": "nikitarodwork@gmail.com",
    	"password": "thisispassword123"
  	}
}

Ответ с сервера:
{"user":{
	"username":"nikitarodyukove",
	"email":"nikitarodwork@gmail.com",
	"token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMGUzMDg4M2NmNzA1MWIwMDgyOWYzMyIsInVzZXJuYW1lIjoibmlraXRhcm9keXVrb3ZlIiwiZXhwIjoxNjY3MDU4NDgwLCJpYXQiOjE2NjE4NzQ0ODB9.P1O8y3oJe8v7wSAt2EDzR2U7yy5qM2kZvhXiNJVKam0"
	}
}

3. Получение данных текущего пользователя

Ответ с сервера:
{"user":{
	"username":"nikitarodyukove",
	"email":"nikitarodwork@gmail.com",
	"token":"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMGUzMDg4M2NmNzA1MWIwMDgyOWYzMyIsInVzZXJuYW1lIjoibmlraXRhcm9keXVrb3ZlIiwiZXhwIjoxNjY3MDU5ODIwLCJpYXQiOjE2NjE4NzU4MjB9.zB3CoYQ_n8D8xJcx4Bur_6XVkfMGX2WgBo1osR8lKx0"
	}
}
