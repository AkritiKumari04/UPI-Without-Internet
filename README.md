# 🚀 Offline UPI Payment System

A secure offline UPI-like payment system prototype built with Java and Spring Boot. The project explores how digital payments can be created, transferred, and synchronized when internet connectivity is unavailable.

## 🌐 Live Demo

https://upi-without-internet-eight.vercel.app/

## 💻 GitHub Repository

https://github.com/AkritiKumari04/UPI-Without-Internet

---

## 🎯 Problem Statement

Digital payments generally depend on internet connectivity. In areas with poor or unavailable connectivity, completing a digital transaction can be difficult.

This project explores an offline-first approach where transactions can be transferred through nearby devices and synchronized with the backend when connectivity becomes available.

---

## 💡 How It Works

```text
Sender
   ↓
Nearby Device
   ↓
Mesh / Gossip Network
   ↓
Bridge Device
   ↓
Backend Server
   ↓
Transaction Settlement
