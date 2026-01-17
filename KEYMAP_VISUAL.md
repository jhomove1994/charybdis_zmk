# 🎹 Charybdis 4x6 Keymap - Colemak-DH Optimizado

> **Configuración basada en nophramel + Vendor Vzhao-L**
> - Firmware: DoctorWangWang ZMK fork (feature-test)
> - Hardware: Nice Nano v2 + Trackball PMW3610 (lado derecho)
> - Layout: Colemak-DH con Home Row Mods
> - Capas: 4 capas optimizadas (BASE, NUM, NAV, SYS)

---

## 📍 Capa 0: BASE (Colemak-DH)

```
╭─────┬─────┬─────┬─────┬─────┬─────╮              ╭─────┬─────┬─────┬─────┬─────┬──────╮
│ ESC │  1  │  2  │  3  │  4  │  5  │              │  6  │  7  │  8  │  9  │  0  │ BKSP │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│ TAB │  Q  │  W  │  F  │  P  │  B  │              │  J  │  L  │  U  │  Y  │  ;  │  \   │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│ DEL │  A  │  R  │  S  │  T  │  G  │              │  M  │  N  │  E  │  I  │  O  │  '   │
│     │CTRL │ ALT │ GUI │SHFT │     │              │     │SHFT │ GUI │ ALT │CTRL │      │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│SHIFT│  Z  │  X  │  C  │  D  │  V  │              │  K  │  H  │  ,  │  .  │  /  │  -   │
╰─────┴─────┴─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┴─────┴─────┴──────╯
                  │ TAB │LCLK │RCLK │              │ RET │BKSP │
                  │ ➊  │     │     │              │ ➊  │     │
                  ╰─────┴─────┴─────╯              ╰─────┴─────╯
                        │ SPC │ ➋  │              │ GUI │
                        │     │     │              │ ➋  │
                        ╰─────┴─────╯              ╰─────╯

      IZQUIERDA (5 teclas)              DERECHA (3 teclas + Trackball)
      ┌─────┬─────┬─────┐               ┌─────┬─────┐
      │ TAB │LCLK │RCLK │               │ RET │BKSP │
      │ ➊  │     │     │               │ ➊  │     │
      ├─────┼─────┼─────┤               └─────┴─────┘
      │ SPC │ ➋  │     │               ┌─────┐
      │     │     │     │               │ GUI │
      └─────┴─────┴─────┘               │ ➋  │
                                        └─────┘
                                        🖱️ Trackball
                                        (tmv_coarse)
```

**Características:**
- ✅ **Colemak-DH**: Layout optimizado para comodidad y velocidad
- ✅ **Home Row Mods**: Modificadores en home row (CTRL, ALT, GUI, SHIFT)
  - **Hold** = Modificador | **Tap** = Letra
  - Solo se activan al presionar teclas del lado opuesto
- ✅ **Layer-tap thumbs**: 
  - ➊ = Layer 1 (NUM) al mantener, TAB/RET al presionar
  - ➋ = Layer 2 (NAV) al mantener, MO(2) en fila inferior izquierda / GUI en fila inferior derecha
- ✅ **Mouse clicks**: LEFT y RIGHT click en fila superior de pulgares (centro)
- ✅ **Trackball**: Movimiento normal del cursor

---

## 🔢 Capa 1: NUMBERS & SYMBOLS

```
╭─────┬─────┬─────┬─────┬─────┬─────╮              ╭─────┬─────┬─────┬─────┬─────┬──────╮
│     │     │     │     │     │     │              │     │     │     │     │     │      │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│  `  │  !  │  @  │  #  │  $  │  %  │              │  ^  │  7  │  8  │  9  │  *  │  |   │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│     │  1  │  2  │  3  │  4  │  5  │              │  +  │  4  │  5  │  6  │  =  │  &   │
│     │CTRL │ ALT │ GUI │SHFT │     │              │     │SHFT │ GUI │ ALT │CTRL │      │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│     │  [  │  ]  │  (  │  )  │  _  │              │  -  │  1  │  2  │  3  │  .  │  \   │
╰─────┴─────┴─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┴─────┴─────┴──────╯
                  │ *** │LCLK │RCLK │              │ *** │  0  │
                  ╰─────┴─────┴─────╯              ╰─────┴─────╯
                        │BKSP │ ➌  │              │ ➌  │
                        ╰─────┴─────╯              ╰─────╯
```

**Características:**
- ✅ **Símbolos** en fila superior: ! @ # $ % ^ * |
- ✅ **Números 1-9** con home row mods en mano izquierda
- ✅ **Numpad** en mano derecha (7 8 9 / 4 5 6 / 1 2 3 / 0)
- ✅ **Operadores**: + - * / = 
- ✅ **Paréntesis**: [ ] ( ) { }
- ✅ **Trackball**: Modo scroll (`tsl`) - mueve para scroll vertical
- ➌ = Activa Layer 3 (SYS) al presionar simultáneamente Layer 1 + 2

---

## 🧭 Capa 2: NAVIGATION & MEDIA

```
╭─────┬─────┬─────┬─────┬─────┬─────╮              ╭─────┬─────┬─────┬─────┬─────┬──────╮
│     │     │     │     │     │     │              │     │     │     │     │     │      │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│     │ F1  │ F2  │ F3  │ F4  │ F5  │              │ F6  │ F7  │ F8  │ F9  │ F10 │ F11  │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│     │HOME │PG_UP│ ⏮  │ ⏯  │ ⏭  │              │     │  ←  │  ↓  │  ↑  │  →  │ F12  │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│     │ END │PG_DN│VOL- │MUTE │VOL+ │              │     │BRI- │BRI+ │     │     │      │
╰─────┴─────┴─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┴─────┴─────┴──────╯
                  │ ➌  │LCLK │RCLK │              │ ➌  │     │
                  ╰─────┴─────┴─────╯              ╰─────┴─────╯
                        │     │ *** │              │ *** │
                        ╰─────┴─────╯              ╰─────╯
```

**Características:**
- ✅ **Teclas F1-F12** distribuidas
- ✅ **Navegación** en home row derecho: ← ↓ ↑ →
- ✅ **Page navigation**: HOME, END, PG_UP, PG_DN
- ✅ **Media controls**: 
  - ⏮ Anterior | ⏯ Play/Pause | ⏭ Siguiente
  - VOL- | MUTE | VOL+
- ✅ **Brillo**: BRI- / BRI+
- ✅ **Trackball**: Modo scroll (`tsl`)
- ➌ = Activa Layer 3 (SYS) al presionar simultáneamente con Layer 1

---

## ⚙️ Capa 3: SYSTEM & BLUETOOTH

```
╭─────────┬─────┬─────┬─────┬─────┬─────╮         ╭─────┬─────┬─────┬─────┬─────┬─────────╮
│BOOTLOAD │     │     │     │     │     │         │     │     │     │     │     │BOOTLOAD │
├─────────┼─────┼─────┼─────┼─────┼─────┤         ├─────┼─────┼─────┼─────┼─────┼─────────┤
│  RESET  │ BT0 │ BT1 │ BT2 │ BT3 │ BT4 │         │ BT4 │ BT3 │ BT2 │ BT1 │ BT0 │ RESET   │
├─────────┼─────┼─────┼─────┼─────┼─────┤         ├─────┼─────┼─────┼─────┼─────┼─────────┤
│         │     │     │     │     │BTCLR│         │BTCLR│     │     │     │     │         │
├─────────┼─────┼─────┼─────┼─────┼─────┤         ├─────┼─────┼─────┼─────┼─────┼─────────┤
│         │     │     │     │     │     │         │     │     │     │     │     │         │
╰─────────┴─────┴─────┼─────┼─────┼─────┤         ├─────┼─────┼─────┴─────┴─────┴─────────╯
                      │ *** │     │ *** │         │ *** │     │
                      ╰─────┴─────┴─────╯         ╰─────┴─────╯
                            │     │     │         │ *** │
                            ╰─────┴─────╯         ╰─────╯
```

**Capa automática - se activa al presionar Layer 1 + 2 simultáneamente**

**Características:**
- ✅ **Bluetooth Profiles**: BT0-BT4 (5 dispositivos)
  - Selecciona dispositivo en ambos lados para fácil acceso
- ✅ **BT CLR**: Limpiar emparejamiento Bluetooth (centro)
- ✅ **RESET**: Reiniciar firmware (esquinas superiores)
- ✅ **BOOTLOADER**: Entrar en modo bootloader para flashear (esquinas top)
- ✅ **Trackball**: Movimiento normal

---

## 🖱️ Configuración del Trackball PMW3610

### Modos por capa

| Capa | Modo | Comportamiento |
|------|------|----------------|
| 0 (BASE) | `tmv_coarse` | Movimiento normal del cursor |
| 1 (NUM) | `tsl` | Scroll vertical (mueve el trackball = scroll) |
| 2 (NAV) | `tsl` | Scroll vertical |
| 3 (SYS) | `tmv_coarse` | Movimiento normal |

### Mouse Clicks

**Ubicación de clicks en pulgares izquierdos (fila superior central):**
```
IZQUIERDA:                    DERECHA:
┌─────┬─────┬─────┐           ┌─────┬─────┐
│ TAB │LCLK │RCLK │           │ RET │BKSP │
│ ➊  │     │     │           │ ➊  │     │
├─────┼─────┼─────┤           └─────┴─────┘
│ SPC │ ➋  │     │           ┌─────┐
│     │     │     │           │ GUI │
└─────┴─────┴─────┘           │ ➋  │
                              └─────┘
```

- **LCLK** (Left Click): Click izquierdo en posición central superior izquierda
- **RCLK** (Right Click): Click derecho en posición derecha superior izquierda
- **GUI** (Win/Cmd): Ahora en botón inferior derecho (RC 4,11)
- Disponibles en capas 0 (BASE), 1 (NUM) y 2 (NAV)

---

## 💡 Funcionalidades Avanzadas

### 1. Home Row Mods

**Técnica de hold-trigger optimizada:**
- Solo se activa el modificador al presionar teclas del **lado opuesto**
- Tapping term: 200ms
- Quick tap: 150ms

**Ejemplo:**
```
Presionar A solo    → Escribe 'a'
Hold A + J          → Control + J (funciona)
Hold A + S          → Solo escribe 'as' (mismo lado, no activa)
```

### 2. Layer-Tap en Pulgares

**Teclas multifunción:**
```
TAB (izq sup izq):
  - Tap rápido: TAB
  - Hold: Layer 1 (NUM)

LCLK/RCLK (izq sup centro/derecha):
  - Solo tap: Left/Right Click

SPC (izq inf izq):
  - Tap rápido: SPACE

MO(2) (izq inf centro):
  - Solo hold: Layer 2 (NAV)

RET (der sup izq):
  - Tap rápido: ENTER
  - Hold: Layer 1 (NUM)

GUI (der inf):
  - Tap rápido: GUI/Win/Cmd
  - Hold: Layer 2 (NAV)
```

### 3. Conditional Layers

**Layer 3 (SYS) se activa automáticamente:**
```
Layer 1 (NUM) + Layer 2 (NAV) = Layer 3 (SYS)
```
No necesitas tecla dedicada para acceder a funciones de sistema.

---

## 🎯 Guía de Uso Rápido

### Uso diario
```
Escribir:          Capa 0 (BASE)
Números:           Hold TAB o ENTER → Capa 1
Navegación:        Hold GUI (der inf) o MO(2) (izq inf centro) → Capa 2
Bluetooth:         Hold TAB + GUI → Capa 3
Scroll:            Activar capa 1 o 2, luego mover trackball
Click izquierdo:   Presionar LCLK (centro superior izquierda)
Click derecho:     Presionar RCLK (derecha superior izquierda)
GUI/Win:           Presionar GUI (botón inferior derecho)
```

### Shortcuts comunes
```
Copy:    Hold S + C (GUI + C en Mac/Linux, CTRL + C en Win)
Paste:   Hold S + V
Cut:     Hold S + X
Undo:    Hold A + Z
Save:    Hold A + S (CTRL + S)
```

### Cambiar dispositivo Bluetooth
```
1. Hold TAB + GUI (activa Layer 3)
2. Presiona BT0, BT1, BT2, BT3 o BT4
3. Suelta TAB + GUI
```

---

## 🚀 Flashear Firmware

```bash
# Descargar de GitHub Actions
cd ~/Downloads
unzip firmware.zip

# Flashear IZQUIERDO
# 1. Conectar USB
# 2. Doble-click RESET
# 3. Copiar archivo
cp charybdis-charybdis_left-nice_nano_v2-zmk.uf2 /Volumes/NICENANO/

# Flashear DERECHO (con trackball)
# 1. Conectar USB
# 2. Doble-click RESET  
# 3. Copiar archivo
cp charybdis-charybdis_right-nice_nano_v2-zmk.uf2 /Volumes/NICENANO/

# Reset settings (si hay problemas)
cp charybdis-settings_reset-nice_nano_v2-zmk.uf2 /Volumes/NICENANO/
```

---

## 📊 Comparación Colemak-DH vs QWERTY

```
Optimizaciones de Colemak-DH:
- Menos movimiento lateral de dedos
- Letras más comunes en home row
- Mejor alternancia entre manos
- Reducción de SFBs (Same Finger Bigrams)

QWERTY:  Q W E R T Y U I O P      Colemak-DH: Q W F P B J L U Y ;
QWERTY:  A S D F G H J K L        Colemak-DH: A R S T G M N E I O
QWERTY:  Z X C V B N M            Colemak-DH: Z X C D V K H , .

Teclas que cambian:
E→F, R→P, T→B, Y→J, U→L, I→U, O→Y, P→;
D→S, F→T, G→(stay), H→M, J→N, K→E, L→I, ;→O
V→D
```

---

*Última actualización: 2026-01-16*  
*Configuración: Vzhao-L (vendor) + nophramel (optimizaciones)*  
*Firmware: DoctorWangWang ZMK fork (feature-test)*  
*Layout: Colemak-DH con Home Row Mods*
