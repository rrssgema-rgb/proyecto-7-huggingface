# Proyecto 7 — Hugging Face Ecosystem

## Objetivo
Desarrollar un clasificador de incidencias de seguros de automóvil utilizando el modelo abierto Qwen3-0.6B y fine-tuning mediante LoRA.

## Contenido
- `Proyecto7_HuggingFace.ipynb`: notebook original con el código y los resultados.
- `entrega_proyecto7.zip`: paquete completo con el informe, los datos sintéticos, las métricas, los resultados y el adaptador LoRA.

## Modelo
- Modelo base: `Qwen/Qwen3-0.6B`
- Técnica: PEFT / LoRA
- Repositorio del adaptador: https://huggingface.co/GMVDD/proyecto7-clasificador-seguros-lora

## Evaluación
Se compararon tres condiciones: modelo base con instrucciones básicas, modelo base con ejemplos (*few-shot*) y modelo ajustado con LoRA. En el conjunto de test utilizado, la condición base con *few-shot* obtuvo los mejores resultados globales.

## Limitaciones
El proyecto utiliza datos sintéticos y una muestra de evaluación reducida. Los resultados son académicos y no deben interpretarse como validación para un sistema de producción.

## Privacidad
Este repositorio de GitHub es privado.
