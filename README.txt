E3T Academic Navigator - Cliente web independiente

Contenido:
- index.html: interfaz de agenda universitaria, tareas personales y consumo de la API REST.

Publicación sugerida:
1. Crear un repositorio GitHub independiente llamado e3t-academic-navigator-web.
2. Subir index.html a la raíz del repositorio.
3. En Settings > Pages, elegir Deploy from a branch, branch main, folder /(root), Save.
4. Abrir la URL GitHub Pages generada.
5. En Configuración de la aplicación, pegar la URL pública del puerto 8000 de Codespaces y pulsar Guardar y conectar.

Notas:
- Las tareas personales se almacenan en localStorage del navegador actual. No se sincronizan entre dispositivos.
- Los compromisos institucionales se consultan en modo de solo lectura mediante la API REST.
- La página no contiene GAS_API_KEY ni otros secretos.
- El asistente IA/MCP se utiliza actualmente desde Copilot Chat en Codespaces; la página ofrece consultas preparadas, pero no simula un chat conectado.
