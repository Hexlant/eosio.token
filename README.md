# eosio.token_example

Compile

$ eosio-cpp -o eosio.token.wasm eosio.token.cpp

$ eosio-cpp -I include -o eosio.token.wasm eosio.token.cpp --abigen

Deploy
  
  $ ./cleos.sh set contract [@Contract Account] ~/{path}/eosio.token_example -p [@Contract Account]
