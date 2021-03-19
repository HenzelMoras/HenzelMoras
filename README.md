

<!--
**HenzelMoras/HenzelMoras** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### motto.sh
```shell
#!/bin/bash
failure() {
    printf "next possible solution\n" >> knowledge.db
}

while :
do
  read -p  "success : " success
    if [[ -z "$success" ]]; then
        read -p "perhaps i'm talking to a ghost? : " dead
        if [[ -n "$dead" ]]; then
            failure
            printf "at times failure is inevitable, what matters is what u learn from it\n"
        else
            echo "Alas! ur journey has come to an end"
            break
        fi
    elif [[ ${success} == false ]]; then
        printf "keep trying ... persistence is key!\n"
        failure                                                                                                                                                 
    else                                                                                                         
        echo "GG ...onto the next problem"                                                                                                  
    fi                                                                                 
done                         
```
###  greetings :vulcan_salute:

- 🌱 I’m currently learning Web security , System Administration
- 👯 I’m looking to collaborate on Python Open Source Projects
- 💬 Ask me about: Python<img src="https://github.com/HenzelMoras/HenzelMoras/blob/5c354a38ecc2682e6ba8ec03ef52e24ee4bcb0b4/images/python.jpg" width="30">, Bash, CLI, Django and so many others.
- 📫 How to reach me: henzelmoras@gmail.com

