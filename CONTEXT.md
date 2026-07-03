# Contexto del Proyecto - Urban FixSolutions

## Descripción
Plataforma de gestión de servicios urbanos para la organización Check-The-Stack.

## Equipo
| Rol | Integrante |
|-----|------------|
| Frontend | Erika Helfenstern |
| Backend | Fernando Galassi |
| QA | Mayra Chazarreta |
| UX/UI | Camille Alcavil |

## Stack Tecnológico
- **Frontend:** React + Vite + Tailwind CSS
- **Backend:** Express + Prisma
- **Base de datos:** PostgreSQL
- **Gestor de paquetes:** pnpm (NO npm)

## Comandos Importantes
```bash
# Instalar dependencias
pnpm install

# Desarrollo
pnpm dev

# Build
pnpm build
```

## Estructura del Proyecto
```
Urban-FixSolutions-G15I0107/
├── frontend/     # React + Vite (Erika)
├── backend/      # Express + Prisma (Fernando)
├── design/       # Wireframes, mockups (Camille)
├── tests/        # Reportes QA (Mayra)
└── docs/
```

## Reglas de Trabajo
1. **Nunca push directo a main** — siempre PR
2. **Cada uno trabaja en su carpeta** — no tocar la de otros sin avisar
3. **Branch naming:** `feature/nombre`, `fix/nombre`, `docs/nombre`
4. **Commits descriptivos:** `feature: agregar formulario de login`
5. **Siempre pull antes de empezar** a trabajar

## Variables de Entorno
### Frontend (.env)
```
VITE_API_URL=http://localhost:3001
```

### Backend (.env)
```
PORT=3001
DATABASE_URL="postgresql://user:password@localhost:5432/urbanfix"
```

## Roles de Usuario
- **CLIENTE** — solicita servicios
- **TECNICO** — acepta y ejecuta servicios
- **ADMIN** — gestiona el sistema

## Diseño Responsive
- Mobile First: diseñar para móvil primero
- Breakpoints de Tailwind: sm(640px), md(768px), lg(1024px), xl(1280px)
- Componentes deben funcionar en todos los tamaños
- Formularios y tablas deben ser responsive
- Navegación adaptativa (hamburger menu en móvil)

## Enlaces Importantes
- Repo: https://github.com/Check-The-Stack/Urban-FixSolutions-G15I0107
- Org: https://github.com/Check-The-Stack
