# 🦆 DUCK BANNER - Kali Linux + Termux

Banner del pato low-poly azul hecho con letras y números (ASCII Art), versión neón optimizada para terminal oscura.

![Pato Neón](https://img.shields.io/badge/DUCK-NEON-00FFFF?style=for-the-badge)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge)
![Termux](https://img.shields.io/badge/Termux-000000?style=for-the-badge)

## ✨ Qué es

- **64 de ancho x 33 de alto** - cabe en Termux en vertical y se ve bien en Kali
- **Centrado automático** - detecta el ancho de tu terminal con `tput cols`
- **Neón por defecto** - cian eléctrico, magenta y amarillo fosforescente
- **Sin dependencias** - solo `bash`

## 🚀 Uso rápido

```bash
git clone https://github.com/TU-USUARIO/duck-banner.git
cd duck-banner
chmod +x duck-banner.sh
./duck-banner.sh
```

### Modos

```bash
./duck-banner.sh         # neón (default, mejor para terminal oscura)
./duck-banner.sh neon    # neón
./duck-banner.sh classic # colores originales del pato
./duck-banner.sh --no-color # solo letras y números
```

## 📦 Archivos

| Archivo | Descripción |
|---------|-------------|
| `duck-banner.sh` | **Versión final v3** - Optimizada Kali + Termux, 64 cols, centrada |
| `duck.sh` | Versión original v1 - 110 cols |
| `duck-neon.sh` | Versión neón v2 - 110 cols |
| `README.md` | Este archivo |

## 🖥️ Ponerlo como banner al abrir la terminal

### Kali Linux (zsh)

```bash
cp duck-banner.sh ~/duck-banner.sh
echo "~/duck-banner.sh" >> ~/.zshrc
```

Si usas bash en Kali:

```bash
echo "~/duck-banner.sh" >> ~/.bashrc
```

### Termux (Android)

```bash
cp duck-banner.sh $HOME/duck-banner.sh
chmod +x $HOME/duck-banner.sh
echo "$HOME/duck-banner.sh" >> ~/.bashrc
```

> Tip Termux: si se ve cortado, aleja el zoom un toque o baja el Font Size en Settings.

## 👨‍💻 Para desarrolladores

Reemplaza `TU-USUARIO` por tu usuario de GitHub en los ejemplos de arriba.

## 📄 Licencia

MIT - Úsalo, modifícalo y compártelo libremente.
