# Taquisocope
Gerador de Frequência  Interface com controle de:
VISÃO GERAL DO PROJETO
📱 Objetivo:

Criar um aplicativo para Android que funcione como:

Osciloscópio (visualização de sinais analógicos via microfone ou porta de áudio)

Gerador de frequência (tom/sinal senoidal, quadrado etc.)

🧩 FERRAMENTAS E TECNOLOGIAS
Linguagem e Frameworks:

Kotlin ou Java para Android nativo

Ou Flutter (Dart) para multiplataforma (mais simples para protótipos)

Bibliotecas úteis:

FFT / DSP: para análise de frequência (Ex: JTransforms, DSPFilters, FFT4g)

AudioTrack / AudioRecord (Android SDK): para gerar e captar áudio

⚙️ FUNCIONALIDADES POR MÓDULO
1. Gerador de Frequência

Interface com controle de:

Tipo de onda: senoidal, quadrada, triangular

Frequência (Hz)

Volume (amplitude)

Backend:

Usar AudioTrack para gerar sinais PCM (ex: 44.1kHz sample rate)

Criar buffers com função sen(x), quadrada, etc.
