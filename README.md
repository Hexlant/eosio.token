# eosio.token_example

Compile

 $ eosiocpp -o eosio.token_example.wast eosio.token.cpp
 
 $ eosiocpp -g eosio.token_example.abi eosio.token.hpp

Deploy
  
  $ ./cleos.sh set contract [@Contract Account] ~/{path}/eosio.token_example -p [@Contract Account]
