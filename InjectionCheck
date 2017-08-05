ifconfig | grep wl | awk -F ':' '{print $1}' > Interfacelist.txt
input="Interfacelist.txt"
while IFS= read -r var
do
  inj=$(aireplay-ng --test $var | grep "Injection is working!" | awk -F " " '{print $2 $3 $4}') 
  if test "$inj" = "Injectionisworking!"
  then
       echo -e "${GREEN}Congrats! $var SUPPORTS INJECTION${NC}"
  else
       echo -e "${RED}Alas! $var does not support packet injection${NC}"
  fi
done < "$input" 

