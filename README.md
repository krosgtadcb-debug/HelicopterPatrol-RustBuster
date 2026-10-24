NPCHelicopter 1.0.14

Plugin cliente-servidor para Rust Legacy sobre Fougerite y RustBuster (autor: Sekete) que añade un helicóptero NPC MI24 controlado por el servidor como evento dinámico.

El servidor gestiona toda la lógica: temporizadores de aparición, recorrido por puntos u órbita, detección y selección de objetivos, vida, daño recibido, derribo, drop de suministros y espera entre eventos. El cliente solo valida los mensajes del protocolo y dibuja el modelo, rotores, misiles, humo, fuego, explosión y caja de suministro.

Incluye configuración en español (intervalos, duración sin daño, ruta, salud, velocidad, detección, etc.), comandos de administrador (/npcheli start, stop, status, damage, reload), compilación de DLL de servidor y cliente, y un AssetBundle visual ya construido (Mi24.unity3d).
