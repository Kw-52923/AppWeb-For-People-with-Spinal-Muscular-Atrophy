# 🧬 SMA LifeLink

**Roche Hackathon 2025** - Eslovenia (Virtual)  
*22-23 Noviembre 2025*

## 🏆 Proyecto

Solución tecnológica para mejorar la calidad de vida de personas con Atrofia Muscular Espinal (SMA), desarrollada en 48 horas durante la Roche Hackathon 2025.



## 💡 El Desafío

Crear herramientas digitales innovadoras que ayuden a personas con distrofia muscular a vivir de forma más independiente y conectada.

## ✨ Características Principales

### Para Pacientes
- 🎯 **Control Facial con IA**: Navegación manos libres usando seguimiento ocular (MediaPipe)
- 🚨 **Botón de Emergencia BCI**: Activación por contacto visual prolongado (3 segundos)
- 💊 **Gestor de Medicación**: Recordatorios inteligentes con alertas de stock
- 🗺️ **Mapa de Dolor**: Registro visual e interactivo de molestias corporales
- 🫁 **Dragon Game**: Terapia respiratoria gamificada con detección de soplido
- 🌍 **Red Social SMA**: Comunidad con eventos accesibles verificados

### Para Cuidadores
- 📋 **Rutinas Terapéuticas**: Guías paso a paso con video y narración
- 📊 **Dashboard de Adherencia**: Seguimiento de tratamientos en tiempo real
- 🔗 **Vinculación de Pacientes**: Sistema de conexión seguro
- 📄 **Informes PDF**: Exportación de datos para consultas médicas

## 🛠️ Tecnologías

- **Frontend**: React 18 + Vite
- **Estilos**: Tailwind CSS
- **IA/CV**: MediaPipe Tasks Vision (Face Landmarker)
- **Iconos**: Lucide React
- **Persistencia**: LocalStorage

## 🚀 Instalación

```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/sma-lifelink.git
cd sma-lifelink

# Instalar dependencias
npm install

# Ejecutar en desarrollo
npm run dev
```

La app estará disponible en `http://localhost:5173`

## 🎮 Funcionalidad de Control Facial

El sistema de navegación por rostro permite:
- **Movimiento del cursor**: Seguimiento de posición de la nariz
- **Click**: Guiño de ojo sostenido (300ms)
- **Scroll**: Movimiento hacia bordes superior/inferior
- **Emergencia**: Boca abierta por 3.5 segundos

```javascript
// Configuración de sensibilidad ajustable
const SENSIBILIDAD = 3.0;
const UMBRAL_EAR_CLICK = 0.27;
const TIEMPO_EMERGENCIA = 3500ms;
```

## 📱 Características de Accesibilidad

- ✅ Botones grandes (min 80px) para temblores
- ✅ Alto contraste y tipografía legible
- ✅ Navegación por voz (narración TTS)
- ✅ Modo reducción de movimiento
- ✅ Diseño responsive mobile-first

## 🎯 Casos de Uso Reales

1. **Emergencia Médica**: Paciente activa SOS con mirada cuando no puede moverse
2. **Adherencia Medicinal**: Sistema detecta olvidos y notifica al cuidador
3. **Fisioterapia Remota**: Cuidador guía ejercicios con instrucciones multimedia
4. **Inclusión Social**: Paciente encuentra eventos 100% accesibles cerca de su zona

## 📊 Impacto

- 🎯 **Autonomía**: Reduce dependencia para tareas digitales básicas
- 💊 **Adherencia**: Mejora seguimiento de tratamientos complejos
- 🤝 **Conexión**: Rompe aislamiento social mediante comunidad verificada
- 📈 **Datos Clínicos**: Genera historial objetivo para médicos

## ⚠️ Estado del Proyecto

Este es un **prototipo funcional MVP** desarrollado en 48 horas. No todas las características están implementadas al 100%:

- ✅ Sistema de navegación facial funcional
- ✅ UI/UX completa y responsiva
- ✅ Flujos principales implementados
- ⚠️ Backend simulado (LocalStorage)
- ⚠️ Sin integración con APIs médicas reales
- ⚠️ Reconocimiento de voz pendiente

## 👥 Equipo
Proyecto desarrollado por:
- [Manu Cabello](https://github.com/ManuCodello)
- [Matias Espinola](https://github.com/espinola-matias) 
- [Keila Gonzalez](https://github.com/espinola-matias) 
- [Sebas Mujica](https://github.com/sebasmujica)
- [Maxi Orué](https://github.com/MaxiOru) 
- [Gaston Duarte](https://github.com/gastonduartem) 

## 🔒 Consideraciones de Privacidad

- Los datos faciales **NO se almacenan** ni transmiten
- Todo el procesamiento de IA ocurre **localmente** en el navegador
- Cumplimiento con GDPR para datos de salud

---

Desarrollado con ❤️ para la comunidad SMA durante Roche Hackathon 2025
