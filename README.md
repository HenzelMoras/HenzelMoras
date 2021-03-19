

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
        fi
    elif [[ ${success} == false ]]; then
        printf "keep trying ... persistence is key!\n"
        failure                                                                                                                                                 
    else                                                                                                         
        echo "GG ...onto the next problem"                                                                            
        break                                                          
    fi                                                                                 
done                         
```
