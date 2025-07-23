🇺🇸 HMV-cli (HackMyVM Command Line Interface)


A command-line tool for the HackMyVM platform.
With HMV-cli you can:

✅ List machines by difficulty
✅ Filter by page or search by name
✅ Download VMs directly
✅ Submit flags
✅ Configure your credentials securely

📦 Installation
bash
Copiar
Editar
git clone https://github.com/bitc0de/HMV-cli
cd HMV-cli
bash setup.sh                # Set your HackMyVM username and password
chmod +x hmvcli              # Make it executable
sudo cp hmvcli /usr/bin      # Optional: add it to PATH for global use
⚙️ Usage
🔐 First time setup:
bash
Copiar
Editar
hmvcli -c
🔎 View machines:
bash
Copiar
Editar
hmvcli -m easy         # List easy machines
hmvcli -m all          # List all machines
hmvcli -m hard --page 2       # Show only page 2
hmvcli -m medium --pages 5    # Iterate through first 5 pages
hmvcli -m all --search Sabulaji  # Search by machine name
⬇️ Download a machine:
bash
Copiar
Editar
hmvcli -d Soul
🏁 Submit a flag:
bash
Copiar
Editar
hmvcli -i FLAG{1234} -vm Soul
🤝 Contributing
Pull requests are welcome!
Want to add features like interactive mode or auto-solver integration? Go ahead 💥

🇪🇸 HMV-cli (Interfaz de línea de comandos para HackMyVM)


Herramienta en consola para HackMyVM.
Con HMV-cli puedes:

✅ Ver máquinas según dificultad
✅ Filtrar por página o buscar por nombre
✅ Descargar máquinas directamente
✅ Enviar flags
✅ Configurar tus credenciales de forma rápida

📦 Instalación
bash
Copiar
Editar
git clone https://github.com/bitc0de/HMV-cli
cd HMV-cli
bash setup.sh                # Configura tu usuario y contraseña
chmod +x hmvcli              # Dale permisos de ejecución
sudo cp hmvcli /usr/bin      # Opcional: para ejecutarlo desde cualquier ruta
⚙️ Uso
🔐 Configuración inicial:
bash
Copiar
Editar
hmvcli -c
🔎 Ver máquinas:
bash
Copiar
Editar
hmvcli -m easy         # Ver máquinas fáciles
hmvcli -m all          # Ver todas las máquinas
hmvcli -m hard --page 2       # Solo la página 2
hmvcli -m medium --pages 5    # Recorre las primeras 5 páginas
hmvcli -m all --search Fuzzz  # Busca una máquina por nombre
⬇️ Descargar una máquina:
bash
Copiar
Editar
hmvcli -d Soul
🏁 Enviar una flag:
bash
Copiar
Editar
hmvcli -i FLAG{1234} -vm Soul
🤝 Contribuir
¡Se aceptan pull requests!
¿Tienes ideas como modo interactivo o integración con auto-solvers? ¡Dale caña!
