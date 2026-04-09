# ������������������� Kiky Notes - Android Releases

Reposit��������rio oficial de releases do aplicativo **Kiky Notes** para Android.

## ������������������� ��������ltima Vers��������o: v1.0.4

**Download Direto:**
- [������������������� app-release.apk](releases/v1.0.4/app-release.apk) - Instala����������������o direta (sideload)
- [������������������� app-release.aab](releases/v1.0.4/app-release.aab) - Google Play Bundle

**Documenta����������������o:**
- [���������������������� Release Notes](releases/v1.0.4/RELEASE_NOTES.md) - O que h�������� de novo
- [������������������� ProGuard Mapping](releases/v1.0.4/mapping.txt) - Debug de crashes

---

## �������������������� Hist��������rico de Vers��������es

### [v1.0.4](releases/v1.0.4/)

### 🐛 Bugs Corrigidos
- Fix: OOM (Out of Memory) em builds do Gradle no Jenkins
- Fix: Crash do daemon Gradle durante CI/CD
### ⚙️ Melhorias
- Otimização de uso de memória no processo de build
- Configurações ultra-conservadoras do Gradle para maior estabilidade
- Redução de workers paralelos para 1 (evita sobrecarga)
- Desabilitação de cache de build no CI/CD
### 🔒 Segurança
- Manutenção de ProGuard mapping para debug de crashes em produção
---
---

---

## ������������������� Como Instalar

### M��������todo 1: Google Play Store (Recomendado)

Acesse a Play Store e busque por "Kiky Notes":
https://play.google.com/store/apps/details?id=com.desk.ocrnotes

### M��������todo 2: Instala����������������o Direta (APK)

1. Baixe o APK da ��������ltima vers��������o:
   wget https://git.librography.org/flashlan/kiky-apps-android-releases/raw/branch/main/releases/v1.0.4/app-release.apk

2. Instale via ADB:
   adb install -r app-release.apk

3. Ou transfira para o dispositivo e instale manualmente
   (Ative "Fontes desconhecidas" nas configura����������������es)

---

## ������������������� Verifica����������������o de Integridade

Todas as releases s��������o:
- ���������������� **Assinadas digitalmente** com keystore oficial
- ���������������� **Geradas automaticamente** via Jenkins CI/CD
- ���������������� **Rastre��������veis** com commit hash e build number
- ���������������� **Verific��������veis** via ProGuard mapping

---

## ������������������� Informa����������������es T��������cnicas

- **Package Name:** com.desk.ocrnotes
- **Min SDK:** 24 (Android 7.0)
- **Target SDK:** 34 (Android 14)
- **Arquitetura:** Universal APK (arm64-v8a, armeabi-v7a, x86, x86_64)

---

## ������������������� Suporte

- **Issues:** https://github.com/kikyapps/issues
- **Email:** support@kiky.app
- **Website:** https://kiky.app

---

**�������������������� Build Autom��������tico:** Jenkins CI/CD
**���������������������� ��������ltima Atualiza����������������o:** 2026-04-09 21:27:38
**���������������������������� Build #339** | **������������������� Commit:** 0069740
