# TP1 : Inversion de Contrôle et Injection de Dépendances

|                      |                                                                  |
|----------------------|------------------------------------------------------------------|
| **Établissement**    | Faculté des Sciences de Sfax, Département d'informatique et des Communications |
| **Matière**          | Architecture MicroServices                                       |
| **Filière**          | MPSRCC1                                                          |
| **Étudiante**        | Amina Najar                                                  |
| **Année universitaire** | 2026-2027                                                     |

## 1. Objectif du TP

- Comprendre le principe de l'Inversion de Contrôle (IoC).
- Mettre en œuvre l'Injection de Dépendances (DI) à travers 4 approches :
    1. Injection de dépendances statique.
    2. Injection de dépendances dynamique via un fichier de configuration (`config.txt`) et la réflexion (`Class.forName`).
    3. Injection de dépendances avec Spring XML.
    4. Injection de dépendances avec les annotations Spring.

## 2. Environnement et outils de travail

| Outil | Version utilisée | 
|-------|------------------|
| Système |  macOS  | 
| JDK | Eclipse Temurin 17.0.20.1 |
| IDE | IntelliJ IDEA 2026.2.3 |
| Maven | Maven intégré à IntelliJ |
| Spring Framework | 7.0.8 (`spring-core`, `spring-beans`, `spring-context`) |
| Git |  2.51.0|
## 3. Préparation de l'environnement
### 3.1 Création du projet

