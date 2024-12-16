# Comandos de Instalación de Zsh

```.bash
sudo apt update
sudo apt install zsh
```

# Cambiar Bash a Zsh 

```.bash
which zsh
chsh -s $(which zsh)
```

## Checking 

```.bash
echo $SHELL
```

# Instalación de Kitty 

```.bash
curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh
mkdir -p ~/.local/bin
ln -sf ~/.local/kitty.app/bin/kitty ~/.local/kitty.app/bin/kitten ~/.local/bin/
```

## Checking

```.bash
kitty --version
```

# Configurar el acceso del sistema 

```.bash
cp ~/.local/kitty.app/share/applications/kitty.desktop ~/.local/share/applications/
cp ~/.local/kitty.app/share/applications/kitty-open.desktop ~/.local/share/applications/

sed -i "s|Icon=kitty|Icon=$(readlink -f ~)/.local/kitty.app/share/icons/hicolor/256x256/apps/kitty.png|g" ~/.local/share/applications/kitty*.desktop
sed -i "s|Exec=kitty|Exec=$(readlink -f ~)/.local/kitty.app/bin/kitty|g" ~/.local/share/applications/kitty*.desktop

echo 'kitty.desktop' > ~/.config/xdg-terminals.list
```

# Recursos

[![Kitty](Kitty.png)](https://sw.kovidgoyal.net/kitty/binary/)  
**Página oficial de Kitty**: Emulador de terminal moderno.

[![Zsh+Kitty+PowerLevel10k](Kitty3.png)](https://www.youtube.com/watch?v=3paEqlLuyV8&t=223s)  
**Tutorial: Zsh + Kitty + PowerLevel10k**: Cómo configurar Zsh con Kitty y PowerLevel10k.

[![Instalación Kitty](Kitty2.png)](https://www.youtube.com/watch?v=ht6PUY7BU6Y)  
**Video de instalación de Kitty**: Pasos detallados para instalar Kitty.


# Recursos Útiles para Zsh y Kitty

| Enlace | Descripción |
|--------|-------------|
| [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md) | Realza la sintaxis en tu terminal para mayor claridad. |
| [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#manual-git-clone) | Sugerencias automáticas de comandos mientras escribes. |
| [Powerlevel10k](https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#for-new-users) | Tema avanzado y personalizable para Zsh. |
| [Nerd Fonts](https://www.nerdfonts.com/font-downloads) | Descarga fuentes con íconos para mejorar tu terminal. |



<p style="text-align: center;">By Omarch ✨🚀</p>

