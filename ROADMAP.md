# ROADMAP — La RST

## 1.0.0 — Noyau fonctionnel (MVP)

- [x] Dépôt initial (`la-rst`)
- [x] Modèle de données (bénévoles, bénéficiaires, missions)
- [x] API REST basique (CRUD)
- [x] Pages HTML simples (liste + formulaire)
- [x] Auth admin simple (token / basic)
- [x] Documentation minimale (README, data-model, architecture)

Objectif : plateforme utilisable en interne par une petite équipe.

---

## 1.1.0 — Confort d’usage & gouvernance

### Fonctionnel

- [x] Système de rôles : admin / coordinateur / bénévole (lecture limitée)
- [x] Filtrage / recherche sur les listes (par nom, statut, mission)
- [x] Historique simple des missions par bénévole / bénéficiaire
- [x] Statut des missions (planifiée, réalisée, annulée)

### Technique

- [x] Ajout de tests automatisés (backend)
- [x] Dockerisation simple (backend + base de données)
- [x] Amélioration de la structure frontend (composants réutilisables)

### Gouvernance & docs

- [x] `governance.md` — rôles, responsabilités, processus de décision
- [x] `data-policy.md` — principes RGPD, minimisation, consentement
- [x] Guide d’installation pour petites associations (docs/)

---

## 1.2.0+ (pistes futures)

- Notifications (email / SMS)
- Interface mobile / PWA
- Statistiques avancées (heures de bénévolat, nombre de missions, etc.)
- Multi‑structures (plusieurs associations sur une même instance)
