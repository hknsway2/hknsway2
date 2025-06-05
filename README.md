# 🚀 OllamaCoder 2.5 - Advanced IDE mit KI-Integration

## 📊 **PROJEKT STATUS**
- **Phase 1**: ✅ **VOLLSTÄNDIG ABGESCHLOSSEN** (Performance Monitoring, MessageBus, Dashboard Integration)
- **Phase 2**: ⚡ **67% ABGESCHLOSSEN** (Code-Completion Optimierung in Arbeit)
- **Build Status**: ✅ **0 TypeScript Fehler** - Vollständig kompilierbar

---

## 🎯 **HAUPT-FEATURES**

### ✅ **Vollständig Implementiert:**
- **Advanced Code-Completion** - Intelligente KI-gestützte Code-Vervollständigung mit 67% Erfolgsquote
- **Performance Monitoring** - Real-time Performance Dashboard mit Sidebar-Integration
- **MessageBus System** - Event-driven Service-Kommunikation
- **TreeSitter Integration** - Multi-Sprachen AST-Parsing (TypeScript, JavaScript, Python, etc.)
- **Project Index Service** - Projektweite Symbol-Indexierung und Cross-file Resolution
- **Ollama Integration** - Lokale KI-Modelle für Code-Generierung
- **Monaco Editor** - Vollständiger VS Code Editor mit Syntax-Highlighting
- **Dateisystem-Integration** - Vollständiger Zugriff auf lokales Dateisystem
- **Terminal Integration** - Eingebautes Terminal mit Multi-Tab-Support

### ⚡ **Phase 2 Optimierung (Aktuell):**
- **Scope Relevance** - Erweiterte lokale Variablen-Erkennung
- **Prefix Matching** - CamelCase/Fuzzy-Matching Verbesserung  
- **Type Matching** - TypeScript AST-Integration Optimierung
- **Cache Performance** - Test-Umgebung Cache-System
- **Completion Relevance** - >90% Top-5 Relevanz-Ziel

---

## 🏗️ **ARCHITEKTUR**

### **Service-Architektur:**
- **IntelligentCodeCompletionService** - 8-stufiger Advanced Ranking Algorithm
- **PerformanceMonitor** - Real-time Metrics & Alert System
- **MessageBus** - Event-driven Communication
- **TreeSitterService** - Multi-Language AST Parsing
- **ProjectIndexService** - Cross-file Symbol Resolution
- **OllamaService** - KI-Integration mit Context-Aware Completions

### **UI-Komponenten:**
- **Performance Dashboard** - Sidebar-integriert mit Real-time Metrics
- **Monaco Editor** - VS Code Editor-Engine
- **File Explorer** - Dateisystem-Navigation
- **Terminal** - Integrierte Shell mit Multi-Tab Support

## Installation

1. Stelle sicher, dass [Ollama](https://ollama.ai) installiert ist und läuft
2. Klone das Repository:
```bash
git clone https://github.com/yourusername/ollamacoder.git
cd ollamacoder
```

3. Installiere die Abhängigkeiten:
```bash
npm install
```

4. Kompiliere und starte die Anwendung:
```bash
npm start
```

## Development

- `npm run dev` - Startet die Anwendung im Entwicklungsmodus
- `npm run watch` - Kompiliert TypeScript-Dateien im Watch-Modus
- `npm run build` - Baut die Anwendung für die Produktion

## Usage

### Dateisystem

OllamaCoder hat vollen Zugriff auf dein lokales Dateisystem. Du kannst:
- Verzeichnisse öffnen
- Dateien erstellen, bearbeiten und löschen
- Unterordner erstellen

### Editor

Der Editor basiert auf dem Monaco-Editor und bietet:
- Syntax-Hervorhebung für verschiedene Sprachen
- Intellisense und Autovervollständigung
- Mehrere geöffnete Tabs
- Tastenkombinationen wie in VS Code (z.B. Strg+S zum Speichern)

### Terminal

Das integrierte Terminal ermöglicht:
- Ausführung von Befehlen direkt im Projektverzeichnis
- Mehrere Terminal-Tabs
- Vollständige Shell-Integration (PowerShell unter Windows, Bash unter Linux/Mac)

### Ollama-Integration

Die Ollama-Integration bietet:
- Auswahl zwischen verschiedenen Modellen
- Chat-Interface für Anfragen an das Modell
- Codegenerierung basierend auf natürlichsprachlichen Beschreibungen
- Kontextuelle Hilfe beim Programmieren

## Voraussetzungen

- Node.js und npm
- Electron
- TypeScript
- React
- Ollama (muss separat installiert sein)

## Lizenz

ISC 
