[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Hello+%F0%9F%91%8B%2C+Sebastien+here.)](https://git.io/typing-svg)

## 🦦 About me
<br>
<ul>
  <li>🚀 Passionate about programming.</li>
  <li>💪🏽 Hard working.</li>
  <li>💡 My Goal: Build products that enhance everyday life for everyone.</li>
  <li>🔍 Curious about uncovering patterns to solve real-world challenges.</li>
</ul>

## 🛠 Area of Interest

```
#include <stdint.h>
#include <stdio.h>

typedef struct {
    const char* role;
    const char* current_favourite[2];
} AREA_OF_INTEREST_t;

/**
 * \fn void print_favourites(AREA_OF_INTEREST_t* in)
 * \param in, data set pointer
 */
void print_favourites(AREA_OF_INTEREST_t* in) {
    const char* favourite_topic[] = {
        "Hardware Design",
        "Algorithms & Data Structure",
        "Software Engineering/Development"
    };
    
    int num_topics = sizeof(favourite_topic) / sizeof(favourite_topic[0]);

    printf("Role: %s\n", in->role);
    printf("Current favourite: %s, %s\n\n", in->current_favourite[0], in->current_favourite[1]);

    for (uint8_t i = 0; i < num_topics; i++) {
        printf("These are my all time %s\n", favourite_topic[i]);
    }
}

int main() {
    AREA_OF_INTEREST_t obj = {
        .role = "Software Engineering",
        .current_favourite = {"C Language", "Python"}
    };

    print_favourites(&obj);

    return 0;
}
```

## 🤖 Tech Stack

🛠 **Language**: Python C++ JavaScript

🐳 **Tools**: GCC 
<!--
**bastoon577-lang/bastoon577-lang** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
