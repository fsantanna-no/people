- ACM TRANSACTIONS ON DESIGN AUTOMATION OF ELECTRONIC SYSTEMS
    - https://todaes.acm.org/editorial_charter.cfm
    - Eng:A2, CS:B1

- Anny tomar as rédeas
    - aplicação deles para Céu

Objetivo:

Desenvolver um sistema "Low-Power Wireless Sensor Network" completo em Céu, incluindo drivers e aplicação, sobre a plataforma Arduino Mini-Ultra-Pro-II da RocketScream:

http://www.rocketscream.com/blog/docs-item/mini-ultra-pro-hookup-guide/

Especificações:
- Microcontrolador ARM Cortex M0+ 32 bits (arm-*.pdf)
- Rádio RF RFM69HCW (rfm69hcw.pdf)
- Sensores ADC quaisquer

Usar o recente suporte de Céu a ISRs e power management.
Sobre Céu:
- Céu em WSNs (sensys-13.pdf)
- ISRs e PM (lctes-18.pdf)
- TCC Guilherme (guilherme-18.pdf)
- Manual (http://fsantanna.github.io/ceu/out/manual/v0.30/)

O que já temos para o M0:
- Driver ADC
- Driver SPI (mais ou menos)
- Modos sleep (mais ou menos)

Próximos passos:
- Ter as diversas partes funcionando em C puro (sem e com ISRs)
- Concluir driver SPI
- Entender as diferenças entre os modos sleep

 arm-m0.pdf
 arm-samd-adc.pdf
 arm-samd-lowpower_techniques.pdf
 arm-samd-standby.pdf
 arm-samd-timers.pdf
 arm-samd.pdf
 rfm69hcw.pdf
 The.Definitive.Guide.to.the.ARM.Cortex-M0_Josep...
