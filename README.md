# 🎓 Regular Expression to Automata Converter

**Theory of Automata - Semester Project 2024**  
**Group 7** | Complete Implementation of Thompson's Construction, Subset Construction, and DFA Minimization

<div align="center">

</div>

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Regular Expression](#-regular-expression)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [How It Works](#-how-it-works)

## 🎯 Overview

This project is a comprehensive web-based implementation of automata theory concepts, demonstrating the complete conversion pipeline from **Regular Expressions → NFA → DFA → Minimized DFA**.

The application provides an interactive visual interface to understand how automata work, featuring:

- Step-by-step state diagrams
- Detailed transition tables
- Real-time string validation simulator
- Educational visualization of automata transformations

### 🎓 Academic Context

Developed as part of the **Theory of Automata** course to demonstrate understanding of:

- Thompson's Construction Algorithm
- Subset Construction Method (Powerset Construction)
- DFA Minimization using Table-Filling Algorithm
- Formal language theory and automata design

## ✨ Features

### 🔷 1. NFA Construction (Thompson's Method)

- Implements Thompson's Construction algorithm from scratch
- Handles union (`+`), concatenation, and Kleene star (`*`) operators
- Supports ε-transitions
- Visual state diagram with clear transition labels
- Complete transition table

### 🔶 2. DFA Conversion (Subset Construction)

- Converts NFA to DFA using subset construction
- Computes ε-closure for all states
- Shows which NFA states are combined into each DFA state
- Visual diagram with optimized state positioning

### 💎 3. DFA Minimization (Table-Filling Algorithm)

- Implements table-filling method for DFA minimization
- Identifies and merges equivalent states
- Shows before/after comparison with statistics
- Highlights merged states and reduction percentage

### 🎮 4. Interactive String Simulator

- Step-by-step execution visualization
- Real-time state transition tracking
- Clear acceptance/rejection feedback
- Quick-test buttons for example strings

### 🎨 5. User Interface

- Modern, responsive Bootstrap design
- Gradient backgrounds and smooth animations
- Tabbed interface
- Color-coded states (Start, Final, Regular)
- Mobile-friendly layout

## 🔤 Regular Expression

The project is built around the following regular expression:

```regex
(g + ggg + gg)*mm + hg + ggh
```
