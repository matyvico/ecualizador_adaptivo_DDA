# Ecualizador Adaptivo DDA
Trabajo práctico final para el curso de postgrado en Diseño Digital Avanzado - Filtro adaptivo

# Software
- Vivado 2017.2
- Verilog 2005

# Hardware
- FPGA Artix-7

# TODO
- Parametrización de los diferentes módulos desarrollados, basados en las declaraciones de macros:
  - [ ] `dsp.v`
  - [ ] `ffe.v`
  - [ ] `lms.v`
  - [ ] `bram.v`
- [ ] Implementación del filtro
- Cálculo de cantidad de bits que vuelven estable las diferentes etapas:
  - [ ] Entrada al `slicer`
  - [ ] Salida de `error`
  - [ ] Coeficientes de corrección calculados
