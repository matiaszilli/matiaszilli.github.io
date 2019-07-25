---
layout: project
type: project
image: images/microservices_cart_cards.jpg
title: Micro Services Cart
permalink: projects/microservices-cart
# All dates must be YYYY-MM-DD format!
date: 2019-04-12
labels:
  - Node.js
  - MongoDB
  - Kubernetes
  - Jenkins
summary: Pequeño proyecto desarrollado en Node.js el cual consta de 4 microservicios (order, account, user, product) el cual fue desplegado sobre Kubernetes en AWS (EKS) utilizando Jenkins.
---

<img class="ui medium right floated rounded image" src="../images/microservices_cart_header.jpg">

El proyecto consiste de un simple shopping cart desarrollado utilizando arquitectura de microservicios.

En total se desarrollaron 4 microservicios (order, account, user, product) utilizando Node.js, cada uno de estos está enlazado a su propia base de datos MongoDB Atlas.

El despliegue se hizo con Jenkins sobre un cluster de Kubernetes fully-managed sobre AWS (EKS), Kubernetes está configurado para realizar escalado automático (cluster_autoscaler) de los workers corriendo en un ASG de EC2. El api gateway se configuró con ingress-nginx controller corriendo sobre el mismo cluster de Kubernetes y soportado por un NLB.

Source: <a href="https://github.com/mzorg"><i class="large github icon "></i>mzorg</a>

