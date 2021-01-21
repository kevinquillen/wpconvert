Dump your data into dirty.csv. Then run this command in the same directory as this project in terminal:

```
docker run -it --rm --name wpconvert -v "$PWD":/usr/src/wpconvert -w /usr/src/wpconvert php:7.4-cli php csv.php
```
