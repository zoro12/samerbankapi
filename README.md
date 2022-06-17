# weather-heroku-samer

add user POST request:
example ..
https://samerbankapi.herokuapp.com/api/user ====> { "passportId":293847564, "cash":90, "credit":78 }

deposit to user POST request:
example ..
https://samerbankapi.herokuapp.com/api/deposit/293847564 ====> body {"cash":99}

credit user POST request:
example ..
https://samerbankapi.herokuapp.com/api/credit/293847564 ====> body {"credit":99}

withdraw from user POST request:
example ..
https://samerbankapi.herokuapp.com/api/withdraw/293847564 ====> body {"amount":99}

transfer from user to another user POST request:
example ..
https://samerbankapi.herokuapp.com/api/withdraw/293847564 ====> body { "from":293847564, "to":345987938, "amount":100 }

get one user by passportId get request:
example ..
https://samerbankapi.herokuapp.com/api/user/293847564

get all users get request:
example ..
https://samerbankapi.herokuapp.com/api/users
