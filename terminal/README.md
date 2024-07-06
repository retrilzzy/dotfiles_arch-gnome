## Настройка терминала

**[ZSH](https://www.zsh.org/) + [Oh My ZSH](https://ohmyz.sh/)**

![terminal](terminal.png)

---

**Тема** [powerlevel10k](https://github.com/romkatv/powerlevel10k)

Конфиг темы: [.p10k.zsh](.p10k.zsh)

Для быстрой конфигурации темы `p10k configure`

---
**Плагины:**
```
plugins=( git zsh-syntax-highlighting zsh-autosuggestions )
```
[zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

[zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

---

**И чуть чуть моей импровизации:**

[exa](https://the.exa.website/) вместо ls

[.zshrc](.zshrc) | Строка 113-116
```
if [ -x "$(command -v exa)" ]; then
    alias ls="exa"
    alias la="exa --long --all --group"
fi7
```