# 🇺🇸 HMV-cli (HackMyVM Command Line Interface)
#Warning.. This project is a fork of the following repository: https://github.com/bitc0de/HMV-cli.git
 I've only added a few features to it.

![HMV-cli](https://i.ibb.co/7V7vPVs/unknown.png)

A command-line tool for the [HackMyVM](https://hackmyvm.eu) platform.  
With HMV-cli you can:

✅ List machines by difficulty  
✅ Filter by page or search by name  
✅ Download VMs directly  
✅ Submit flags  
✅ Configure your credentials securely

---

## 📦 Installation

```bash
git clone https://github.com/bitc0de/HMV-cli
cd HMV-cli
bash setup.sh                # Set your HackMyVM username and password
chmod +x hmvcli              # Make it executable
sudo cp hmvcli /usr/bin      # Optional: add it to PATH for global use
```

---

## ⚙️ Usage

### 🔐 First time setup:

```bash
hmvcli -c
```

---

### 🔎 View machines:

```bash
hmvcli -m easy                   # List easy machines
hmvcli -m all                    # List all machines
hmvcli -m hard --page 2          # Show only page 2
hmvcli -m medium --pages 5       # Iterate through first 5 pages
hmvcli -m all --search Sabulaji  # Search by machine name
```

---

### ⬇️ Download a machine:

```bash
hmvcli -d Soul
```

---

### 🏁 Submit a flag:

```bash
hmvcli -i FLAG{1234} -vm Soul
```

---

## 🤝 Contributing

Pull requests are welcome!  
Want to add features like interactive mode or auto-solver integration? Go ahead 💥

---

# 🇪🇸 HMV-cli (Interfaz de línea de comandos para HackMyVM)
#Advertencia.. este proyecto es un fork de el siguiente repositorio: https://github.com/bitc0de/HMV-cli.git
solo le he agregado algunas funciones.

![HMV-cli](https://i.ibb.co/7V7vPVs/unknown.png)

Herramienta en consola para [HackMyVM](https://hackmyvm.eu).  
Con HMV-cli puedes:

✅ Ver máquinas según dificultad  
✅ Filtrar por página o buscar por nombre  
✅ Descargar máquinas directamente  
✅ Enviar flags  
✅ Configurar tus credenciales de forma rápida

---

## 📦 Instalación

```bash
git clone https://github.com/bitc0de/HMV-cli
cd HMV-cli
bash setup.sh                # Configura tu usuario y contraseña
chmod +x hmvcli              # Dale permisos de ejecución
sudo cp hmvcli /usr/bin      # Opcional: para ejecutarlo desde cualquier ruta
```

---

## ⚙️ Uso

### 🔐 Configuración inicial:

```bash
hmvcli -c
```

---

### 🔎 Ver máquinas:

```bash
hmvcli -m easy                   # Ver máquinas fáciles
hmvcli -m all                    # Ver todas las máquinas
hmvcli -m hard --page 2          # Solo la página 2
hmvcli -m medium --pages 5       # Recorre las primeras 5 páginas
hmvcli -m all --search Fuzzz     # Busca una máquina por nombre
```

---

### ⬇️ Descargar una máquina:

```bash
hmvcli -d Soul
```

---

### 🏁 Enviar una flag:

```bash
hmvcli -i FLAG{1234} -vm Soul
```

---

## 🤝 Contribuir

¡Se aceptan pull requests!  
¿Tienes ideas como modo interactivo o integración con auto-solvers? ¡Dale caña!
