# pigro-verse-test2
Debian Test Repo


```
curl -s --compressed "https://actionschnitzel.github.io/pigro-verse-test2/pigro-verse-test2-key.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/pigro-verse-test2-key.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/pigro-verse-test2.list "https://actionschnitzel.github.io/pigro-verse-test2/pigro-verse-test2.list"
sudo apt update
```