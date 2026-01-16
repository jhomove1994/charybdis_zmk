# 🎹 Charybdis 4x6 Keymap - Colemak-DH

> **Configuración del vendedor Vzhao-L con layout Colemak-DH**
> - Firmware: DoctorWangWang ZMK fork (feature-test)
> - Hardware: Nice Nano v2 + Trackball PMW3610 (lado derecho)
> - Layout: Colemak-DH modificado

---

## 📍 Capa 0: BASE (Colemak-DH)

```
╭─────┬─────┬─────┬─────┬─────┬─────╮              ╭─────┬─────┬─────┬─────┬─────┬──────╮
│ ESC │  1  │  2  │  3  │  4  │  5  │              │  6  │  7  │  8  │  9  │  0  │ BKSP │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│ TAB │  Q  │  W  │  F  │  P  │  B  │              │  J  │  L  │  U  │  Y  │  ;  │  \   │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│SHIFT│  A  │  R  │  S  │  T  │  G  │              │  M  │  N  │  E  │  I  │  O  │  '   │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│CTRL │  Z  │  X  │  C  │  D  │  V  │              │  K  │  H  │  ,  │  .  │  /  │  -   │
╰─────┴─────┴─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┴─────┴─────┴──────╯
                  │ GUI │ SPC │ L1  │              │ ALT │  `  │
                  ╰─────┴─────┴─────╯              ╰─────┴─────╯
                        │RCLK │LCLK │              │ ENT │
                        ╰─────┴─────╯              ╰─────╯

      IZQUIERDA (5 teclas)              DERECHA (3 teclas + Trackball)
      ┌─────┬─────┬─────┐               ┌─────┬─────┐
      │ GUI │ SPC │ L1  │               │ ALT │  `  │
      ├─────┼─────┼─────┤               └─────┴─────┘
      │RCLK │LCLK │     │               ┌─────┐
      └─────┴─────┘     │               │ ENT │
                        │               └─────┘
                        │               🖱️ Trackball
                        │               (movimiento cursor)
```

**Características:**
- Layout: **Colemak-DH** (optimizado para comodidad)
- Trackball: Movimiento de cursor en modo normal (`tmv_coarse`)
- Thumbs L: Win, Espacio, Layer 1, Click derecho, Click izquierdo
- Thumbs R: Alt, Tilde, Enter

---

## ⚙️ Capa 1: SÍMBOLOS Y NAVEGACIÓN

```
╭─────┬─────┬─────┬─────┬─────┬─────╮              ╭─────┬─────┬─────┬─────┬─────┬──────╮
│ F1  │ F2  │ F3  │ F4  │ F5  │ F6  │              │ F7  │ F8  │ F9  │ F10 │ F11 │ F12  │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│CAPS │     │     │     │     │BT▶  │              │     │     │  ↑  │     │     │      │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│SHIFT│     │     │     │     │BT✖  │              │     │  ←  │  ↓  │  →  │     │      │
├─────┼─────┼─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┼─────┼─────┼──────┤
│CTRL │     │     │     │     │     │              │     │     │  .  │  ]  │     │  =   │
╰─────┴─────┴─────┼─────┼─────┼─────┤              ├─────┼─────┼─────┴─────┴─────┴──────╯
                  │ GUI │ SPC │ *** │              │ ALT │ DEL │
                  ╰─────┴─────┴─────╯              ╰─────┴─────╯
                        │RCLK │LCLK │              │ ENT │
                        ╰─────┴─────╯              ╰─────╯
```

**Características:**
- Fila superior: **Teclas F1-F12**
- Bluetooth: `BT▶` = Siguiente dispositivo, `BT✖` = Limpiar emparejamiento
- Navegación: **Flechas** en posición vim (HJKL → ←↓→)
- Trackball: **Modo scroll** (`tsl`) - mueve para hacer scroll

**Notas:**
- `***` = Layer activo (hold para mantener)
- Posición CAPS LOCK en esta capa

---

## 🖱️ Trackball PMW3610 - Configuración

### Hardware
```
Conexión SPI (lado derecho):
┌─────────────────────┐
│ SCK:  Pin 8         │
│ MOSI: Pin 17        │
│ MISO: Pin 17 (3-wire)│
│ CS:   P0.20         │
│ IRQ:  P0.06         │
└─────────────────────┘

Matriz GPIO:
- Filas: P0.31, P1.15, P0.24, P0.22, P1.6
- Columnas: P0.2, P0.29, P0.9, P1.0, P0.11, P1.4
```

### Modos de operación

| Capa | Modo Trackball | Descripción |
|------|----------------|-------------|
| 0    | `tmv_coarse`   | Movimiento normal del cursor |
| 1    | `tsl`          | Modo scroll (vertical/horizontal) |

**Uso:**
- **Capa 0**: Mueve el trackball → cursor se mueve
- **Capa 1** (hold Layer 1): Mueve el trackball → scroll vertical
- **Clicks**: Usa teclas RCLK/LCLK en pulgares izquierdos

---

## 🔧 Distribución física del teclado

```
┌─────────────────────┐              ┌─────────────────────┐
│   Teclas 4x6        │              │   Teclas 4x6        │
│   (24 teclas)       │              │   (24 teclas)       │
├─────────────────────┤              ├─────────────────────┤
│ Pulgares (5 teclas) │              │ Pulgares (3 teclas) │
│  ┌───┬───┬───┐      │              │  ┌───┬───┐          │
│  │GUI│SPC│L1 │      │              │  │ALT│ ` │          │
│  ├───┼───┼───┤      │              │  └───┴───┘          │
│  │RCK│LCK│   │      │              │  ┌───┐              │
│  └───┴───┘   │      │              │  │ENT│              │
└───────────────┘      │              │  └───┘              │
  Lado IZQUIERDO       │              └─────────────────────┘
                       │                 Lado DERECHO
                       │              ┌─────────────────────┐
                       │              │   🖱️ Trackball      │
                       │              │   PMW3610 (físico)  │
                       │              └─────────────────────┘
```

---

## 📝 Notas importantes

### Colemak-DH vs QWERTY
```
Cambios principales:
QWERTY: Q W E R T Y U I O P
        ↓ ↓ ↓ ↓ ↓ ↓ ↓ ↓ ↓ ↓
Colemak: Q W F P B J L U Y ;

QWERTY: A S D F G H J K L
        ↓ ↓ ↓ ↓ ↓ ↓ ↓ ↓ ↓
Colemak: A R S T G M N E I O

Fila inferior casi igual, solo D y V intercambiados
```

### Teclas especiales
- **Layer 1**: Hold tecla "L1" en pulgar derecho superior
- **Mouse clicks**: RCLK/LCLK en fila inferior de pulgares izquierdos
- **Bluetooth**: Disponible en Layer 1
  - `BT▶` (BT_NXT): Cambiar dispositivo emparejado
  - `BT✖` (BT_CLR): Limpiar emparejamientos

### Configuración ZMK
```yaml
# west.yml
remote: DoctorWangWang/zmk
revision: feature-test

Soporte nativo de:
- Trackball PMW3610
- Mouse keys (mkp)
- Pointing device
```

---

## 🚀 Flashear firmware

```bash
# Descargar firmware de GitHub Actions
cd ~/Downloads
unzip firmware.zip

# Flashear lado IZQUIERDO
# 1. Conecta Nice Nano izquierdo via USB
# 2. Presiona botón RESET 2 veces (aparece como NICENANO)
cp charybdis-charybdis_left-nice_nano_v2-zmk.uf2 /Volumes/NICENANO/

# Flashear lado DERECHO (con trackball)
# 1. Conecta Nice Nano derecho via USB
# 2. Presiona botón RESET 2 veces
cp charybdis-charybdis_right-nice_nano_v2-zmk.uf2 /Volumes/NICENANO/
```

---

*Última actualización: 2026-01-16*  
*Configuración: Vzhao-L vendor + Colemak-DH*  
*Firmware: DoctorWangWang ZMK (feature-test)*
