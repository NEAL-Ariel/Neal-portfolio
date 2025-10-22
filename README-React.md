# Portfolio React - Neal TOKPO

## 🚀 Modernisation avec React

Votre portfolio a été modernisé avec React pour une expérience utilisateur améliorée et un code plus maintenable.

## 📁 Structure du projet

```
D:\Mon portfolie\
├── index.html          # Ancien portfolio (HTML/CSS/JS)
├── index-react.html    # Nouveau portfolio React
├── app.jsx            # Application React principale
├── styles-react.css   # Styles CSS modernes
├── README-React.md    # Ce fichier
└── [images...]        # Vos images existantes
```

## ✨ Nouvelles fonctionnalités

### 🎨 Design moderne
- **Interface responsive** : Adaptée à tous les écrans (desktop, tablette, mobile)
- **Animations fluides** : Transitions et effets visuels modernes
- **Design system cohérent** : Variables CSS, couleurs harmonisées
- **Navigation fixe** : Menu qui reste visible lors du scroll
- **Effets visuels** : Éléments flottants et animations de texte

### ⚡ Interactions React
- **Navigation fluide** : Scroll automatique vers les sections
- **Formulaire interactif** : Gestion d'état avec React hooks
- **Animations progressives** : Barres de compétences animées
- **Effets de survol** : Interactions visuelles améliorées
- **Textes dynamiques** : Animation de changement de titre
- **Boutons interactifs** : États de chargement et feedback

### 🔧 Composants modulaires
- **🏠 Accueil (Hero)** : Présentation dynamique avec photo et animations
- **👨‍💻 À propos** : Parcours détaillé, compétences et CV téléchargeable
- **🛠️ Projets** : Galerie de projets avec cartes et boutons "Voir plus"
- **📞 Contact** : Formulaire avancé + liens vers réseaux sociaux
- **Navigation** : Menu avec émojis et scroll fluide
- **Footer** : Pied de page simple et élégant

## 🚀 Comment utiliser

### Option 1 : Ouvrir directement
1. Ouvrez `index-react.html` dans votre navigateur
2. C'est tout ! Votre portfolio React est prêt

### Option 2 : Serveur local (recommandé)
Si vous avez Python installé :
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Puis ouvrez `http://localhost:8000/index-react.html`

## 🎯 Personnalisation

### Modifier le contenu
Éditez le fichier `app.jsx` pour :

**🏠 Page d'accueil :**
- Modifier le texte de présentation
- Changer les titres dynamiques (lignes 42-45)
- Personnaliser les boutons d'action

**👨‍💻 Page À propos :**
- Mettre à jour votre parcours (lignes 140-156)
- Modifier les compétences et niveaux (lignes 131-138)
- Personnaliser les liens sociaux

**🛠️ Page Projets :**
- Ajouter/modifier vos projets (lignes 255-316)
- Changer les images, descriptions et technologies
- Mettre à jour les liens GitHub et démos

**📞 Page Contact :**
- Modifier les informations de contact (lignes 402-421)
- Personnaliser les réseaux sociaux (lignes 423-454)
- Adapter le formulaire selon vos besoins

### Modifier le design
Éditez le fichier `styles-react.css` pour :
- Changer les couleurs (variables CSS en haut du fichier)
- Modifier les polices
- Ajuster les espacements
- Personnaliser les animations

### Ajouter des fonctionnalités
- **Formulaire de contact** : Connectez-le à un service d'email
- **Portfolio de projets** : Ajoutez une section avec vos réalisations
- **Blog** : Intégrez un système de blog
- **Multilingue** : Ajoutez le support de plusieurs langues

## 🔗 Liens sociaux

Modifiez les liens dans le composant `SocialBar` (ligne ~50 de `app.jsx`) :
```jsx
const socialLinks = [
    { icon: 'fab fa-github', name: 'GitHub', url: 'https://github.com/votre-profil' },
    { icon: 'fab fa-linkedin', name: 'LinkedIn', url: 'https://linkedin.com/in/votre-profil' },
    // ...
];
```

## 📱 Responsive Design

Le design s'adapte automatiquement :
- **Desktop** : Layout en grille, navigation horizontale
- **Tablette** : Colonnes empilées, navigation simplifiée
- **Mobile** : Design vertical, boutons tactiles optimisés

## 🚀 Prochaines étapes

### Pour aller plus loin avec React
1. **Installer Node.js** : Pour utiliser les outils de développement
2. **Create React App** : Pour un environnement de développement complet
3. **State Management** : Redux ou Context API pour des applications complexes
4. **Routing** : React Router pour des pages multiples
5. **Build Tools** : Webpack, Vite pour l'optimisation

### Améliorations suggérées
- [ ] Ajouter une section portfolio avec vos projets
- [ ] Intégrer un système de contact (EmailJS, Netlify Forms)
- [ ] Ajouter des animations plus avancées (Framer Motion)
- [ ] Implémenter le mode sombre/clair
- [ ] Ajouter des tests unitaires
- [ ] Optimiser les images et le SEO

## 🆚 Comparaison

| Fonctionnalité | Ancien (HTML/CSS) | Nouveau (React) |
|---|---|---|
| **Maintenance** | Code monolithique | Composants modulaires |
| **Interactions** | JavaScript basique | Hooks React avancés |
| **Responsive** | CSS basique | Design system complet |
| **Animations** | CSS statique | Animations fluides |
| **Performance** | Standard | Optimisé React |
| **Évolutivité** | Difficile | Facile à étendre |

## 🎉 Félicitations !

Votre portfolio est maintenant modernisé avec React ! Vous avez une base solide pour continuer à développer votre présence en ligne professionnelle.

---

*Développé avec ❤️ en React*




                    <h3 style="color: var(--accent-color); margin-bottom: 1.5rem; font-size: 1.5rem;"><i class="fas fa-server"></i> Back-End</h3>
                    <div style="margin-bottom: 1rem;">
                        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.5rem;">
                            <span style="font-weight: 600; color: #e2e8f0;">Node.js / Express</span>
                            <span style="color: var(--secondary-color); font-weight: 700;">80%</span>
                        </div>
                        <div style="width: 100%; height: 8px; background: rgba(248, 250, 252, 0.1); border-radius: 4px; overflow: hidden;">
                            <div style="height: 100%; width: 80%; background: linear-gradient(90deg, #ec4899, #f472b6); border-radius: 4px; transition: width 2s ease; box-shadow: 0 0 10px rgba(236, 72, 153, 0.5);"></div>
                        </div>
                    </div>
                    <div style="margin-bottom: 1rem;">
                        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.5rem;">
                            <span style="font-weight: 600; color: #e2e8f0;">Python / Django</span>
                            <span style="color: var(--secondary-color); font-weight: 700;">70%</span>
                        </div>
                        <div style="width: 100%; height: 8px; background: rgba(248, 250, 252, 0.1); border-radius: 4px; overflow: hidden;">
                            <div style="height: 100%; width: 70%; background: linear-gradient(90deg, #ec4899, #f472b6); border-radius: 4px; transition: width 2s ease; box-shadow: 0 0 10px rgba(236, 72, 153, 0.5);"></div>
                        </div>
                    </div>
                    <div style="margin-bottom: 1rem;">
                        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.5rem;">
                            <span style="font-weight: 600; color: #e2e8f0;">API REST</span>
                            <span style="color: var(--secondary-color); font-weight: 700;">85%</span>
                        </div>
                        <div style="width: 100%; height: 8px; background: rgba(248, 250, 252, 0.1); border-radius: 4px; overflow: hidden;">
                            <div style="height: 100%; width: 85%; background: linear-gradient(90deg, #ec4899, #f472b6); border-radius: 4px; transition: width 2s ease; box-shadow: 0 0 10px rgba(236, 72, 153, 0.5);"></div>
                        </div>
                    </div>
                </div>
                
                <div style="background: rgba(99, 102, 241, 0.1); padding: 1.5rem; border-radius: var(--border-radius); border: 1px solid rgba(99, 102, 241, 0.3); backdrop-filter: blur(10px);">
                    <h3 style="color: var(--secondary-color); margin-bottom: 1.5rem; font-size: 1.5rem;"><i class="fas fa-database"></i> Base de Données</h3>
                    <div style="margin-bottom: 1rem;">
                        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.5rem;">
                            <span style="font-weight: 600; color: #e2e8f0;">MongoDB</span>
                            <span style="color: var(--accent-color); font-weight: 700;">80%</span>
                        </div>
                        <div style="width: 100%; height: 8px; background: rgba(248, 250, 252, 0.1); border-radius: 4px; overflow: hidden;">
                            <div style="height: 100%; width: 80%; background: linear-gradient(90deg, #6366f1, #a5b4fc); border-radius: 4px; transition: width 2s ease; box-shadow: 0 0 10px rgba(99, 102, 241, 0.5);"></div>
                        </div>
                    </div>
                    <div style="margin-bottom: 1rem;">
                        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.5rem;">
                            <span style="font-weight: 600; color: #e2e8f0;">PostgreSQL</span>
                            <span style="color: var(--accent-color); font-weight: 700;">75%</span>
                        </div>
                        <div style="width: 100%; height: 8px; background: rgba(248, 250, 252, 0.1); border-radius: 4px; overflow: hidden;">
                            <div style="height: 100%; width: 75%; background: linear-gradient(90deg, #6366f1, #a5b4fc); border-radius: 4px; transition: width 2s ease; box-shadow: 0 0 10px rgba(99, 102, 241, 0.5);"></div>
                        </div>
                    </div>
                    <div style="margin-bottom: 1rem;">
                        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.5rem;">
                            <span style="font-weight: 600; color: #e2e8f0;">MySQL</span>
                            <span style="color: var(--accent-color); font-weight: 700;">70%</span>
                        </div>
                        <div style="width: 100%; height: 8px; background: rgba(248, 250, 252, 0.1); border-radius: 4px; overflow: hidden;">
                            <div style="height: 100%; width: 70%; background: linear-gradient(90deg, #6366f1, #a5b4fc); border-radius: 4px; transition: width 2s ease; box-shadow: 0 0 10px rgba(99, 102, 241, 0.5);"></div>
                        </div>
                    </div>
                </div>
                
                <div style="background: rgba(236, 72, 153, 0.1); padding: 1.5rem; border-radius: var(--border-radius); border: 1px solid rgba(236, 72, 153, 0.3); backdrop-filter: blur(10px);">


                information contact

                 <!-- Contact Section -->
<section style="
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 95vh; /* ✅ Presque toute la hauteur de l'écran */
    background: linear-gradient(135deg, rgba(99, 102, 241, 0.05) 0%, rgba(236, 72, 153, 0.05) 100%);
    padding: 3rem;
">
    <div style="animation: slideInLeft 0.8s ease-out;"> 
        <div style="
            background: rgba(30, 41, 59, 0.85);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(99, 102, 241, 0.3);
            border-radius: 20px;
            padding: 2.5rem; /* ✅ Moins de padding */
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
            max-width: 750px; /* ✅ Contenu légèrement réduit */
            width: 100%;
        ">
            <h3 style="color: var(--secondary-color); text-align: center; margin-bottom: 2rem; font-size: 1.8rem; font-weight: 600;">
                <i class="fas fa-address-card" style="margin-right: 0.5rem; font-size: 1.6rem;"></i>
                Informations de contact
            </h3>

            <!-- Cartes de contact -->
            <div style="display: flex; flex-direction: column; gap: 1.2rem; margin-bottom: 2rem;">
                <!-- Email -->
                <div style="background: linear-gradient(135deg, rgba(99, 102, 241, 0.2), rgba(165, 180, 252, 0.1));
                    padding: 1.2rem; border-radius: 12px; display: flex; align-items: center; gap: 1.2rem;
                    border: 1px solid rgba(99, 102, 241, 0.3);">
                    <div style="background: var(--gradient-accent); color: var(--text-light);
                        width: 45px; height: 45px; border-radius: 50%; display: flex; align-items: center;
                        justify-content: center; font-size: 1.1rem;">
                        <i class="fas fa-envelope"></i>
                    </div>
                    <div>
                        <h4 style="color: var(--secondary-color); margin-bottom: 0.3rem; font-size: 1.1rem; font-weight: 600;">Email</h4>
                        <p style="margin: 0; color: var(--text-light); font-size: 0.95rem;">neal.tokpo@example.com</p>
                    </div>
                </div>

                <!-- GitHub -->
                <div style="background: linear-gradient(135deg, rgba(236, 72, 153, 0.2), rgba(165, 180, 252, 0.1));
                    padding: 1.2rem; border-radius: 12px; display: flex; align-items: center; gap: 1.2rem;
                    border: 1px solid rgba(236, 72, 153, 0.3);">
                    <div style="background: var(--gradient-secondary); color: var(--text-light);
                        width: 45px; height: 45px; border-radius: 50%; display: flex; align-items: center;
                        justify-content: center; font-size: 1.1rem;">
                        <i class="fab fa-github"></i>
                    </div>
                    <div>
                        <h4 style="color: var(--accent-color); margin-bottom: 0.3rem; font-size: 1.1rem; font-weight: 600;">GitHub</h4>
                        <p style="margin: 0; color: var(--text-light); font-size: 0.95rem;">github.com/neal-tokpo</p>
                    </div>
                </div>

                <!-- Localisation -->
                <div style="background: linear-gradient(135deg, rgba(99, 102, 241, 0.2), rgba(236, 72, 153, 0.1));
                    padding: 1.2rem; border-radius: 12px; display: flex; align-items: center; gap: 1.2rem;
                    border: 1px solid rgba(99, 102, 241, 0.3);">
                    <div style="background: linear-gradient(135deg, #6366f1, #ec4899); color: var(--text-light);
                        width: 45px; height: 45px; border-radius: 50%; display: flex; align-items: center;
                        justify-content: center; font-size: 1.1rem;">
                        <i class="fas fa-map-marker-alt"></i>
                    </div>
                    <div>
                        <h4 style="color: var(--secondary-color); margin-bottom: 0.3rem; font-size: 1.1rem; font-weight: 600;">Localisation</h4>
                        <p style="margin: 0; color: var(--text-light); font-size: 0.95rem;">Cotonou, Bénin</p>
                    </div>
                </div>
            </div>

            <!-- Réseaux sociaux -->
            <div>
                <h4 style="color: var(--secondary-color); font-size: 1.5rem; margin-bottom: 1.5rem; text-align: center; font-weight: 600;">
                    <i class="fas fa-share-alt" style="margin-right: 0.5rem;"></i>
                    Suivez-moi
                </h4>
                <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem;">
                    <!-- GitHub -->
                    <a href="https://github.com/neal-tokpo" target="_blank" style="background: linear-gradient(135deg, rgba(51, 51, 51, 0.3), rgba(99, 102, 241, 0.1));
                        padding: 1.2rem; border-radius: 12px; text-decoration: none; color: var(--text-light);
                        display: flex; flex-direction: column; align-items: center; gap: 0.6rem;
                        border: 1px solid rgba(99, 102, 241, 0.3); transition: var(--transition);">
                        <div style="background: #333; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center;">
                            <i class="fab fa-github"></i>
                        </div>
                        <span style="font-size: 0.95rem; font-weight: 600;">GitHub</span>
                    </a>

                    <!-- LinkedIn -->
                    <a href="https://linkedin.com/in/neal-tokpo" target="_blank" style="background: linear-gradient(135deg, rgba(0, 119, 181, 0.3), rgba(99, 102, 241, 0.1));
                        padding: 1.2rem; border-radius: 12px; text-decoration: none; color: var(--text-light);
                        display: flex; flex-direction: column; align-items: center; gap: 0.6rem;
                        border: 1px solid rgba(0, 119, 181, 0.3);">
                        <div style="background: #0077b5; color: white; width: 40px; height: 40px; border-radius: 50%; display: flex; align-items: center; justify-content: center;">
                            <i class="fab fa-linkedin"></i>
                        </div>
                        <span style="font-size: 0.95rem; font-weight: 600;">LinkedIn</span>
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- About Section -->
    <section id="about" style="padding: 4rem 2rem; background: rgba(99, 102, 241, 0.05); backdrop-filter: blur(10px);">
        <div style="max-width: 1200px; margin: 0 auto;">
            <h2 class="section-title">👨‍💻 À PROPOS DE MOI</h2>
            <p class="section-subtitle">
                Développeur web passionné, spécialisé en front-end et en design UI/UX
            </p>
            
            <div class="about-container" style="display: grid; grid-template-columns: 1fr; gap: 3rem; align-items: start;">
                <!-- Card principale avec image et contenu -->
                <div style="background: rgba(30, 41, 59, 0.6); backdrop-filter: blur(15px); border-radius: 25px; padding: 3rem; border: 1px solid rgba(99, 102, 241, 0.3); box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);">
                    <div style="display: grid; grid-template-columns: 300px 1fr; gap: 3rem; align-items: center;">
                        <!-- Image et nom -->
                        <div style="text-align: center;">
                            <div style="position: relative; display: inline-block; margin-bottom: 1.5rem;">
                                <img src="photo1.jpg" alt="Neal TOKPO" style="width: 250px; height: 250px; border-radius: 50%; box-shadow: 0 15px 35px rgba(99, 102, 241, 0.5); object-fit: cover; border: 5px solid rgba(99, 102, 241, 0.4);">
                            </div>
                            <h3 style="margin-bottom: 0.5rem; color: var(--text-light); font-size: 1.5rem; font-weight: 700;">Neal TOKPO</h3>
                            <p style="color: var(--secondary-color); font-size: 1.1rem; margin-bottom: 1rem;">Développeur Fullstack</p>
                            <div style="display: flex; gap: 1rem; justify-content: center; margin-top: 1.5rem;">
                                <a href="#" style="width: 45px; height: 45px; background: rgba(99, 102, 241, 0.2); color: var(--secondary-color); border-radius: 50%; display: flex; align-items: center; justify-content: center; text-decoration: none; transition: var(--transition); border: 1px solid rgba(99, 102, 241, 0.3);">
                                    <i class="fab fa-linkedin-in"></i>
                                </a>
                                <a href="#" style="width: 45px; height: 45px; background: rgba(99, 102, 241, 0.2); color: var(--secondary-color); border-radius: 50%; display: flex; align-items: center; justify-content: center; text-decoration: none; transition: var(--transition); border: 1px solid rgba(99, 102, 241, 0.3);">
                                    <i class="fab fa-github"></i>
                                </a>
                                <a href="#" style="width: 45px; height: 45px; background: rgba(99, 102, 241, 0.2); color: var(--secondary-color); border-radius: 50%; display: flex; align-items: center; justify-content: center; text-decoration: none; transition: var(--transition); border: 1px solid rgba(99, 102, 241, 0.3);">
                                    <i class="fab fa-twitter"></i>
                                </a>
                            </div>
                        </div>
                        
                        <!-- Contenu texte -->
                        <div>
                            <div style="margin-bottom: 2rem;">
                                <h4 style="color: var(--accent-color); font-size: 1.3rem; margin-bottom: 1rem; display: flex; align-items: center; gap: 0.5rem;">
                                    <i class="fas fa-user-circle"></i> Mon Parcours
                                </h4>
                                <p style="margin-bottom: 1rem; font-size: 1.1rem; color: #cbd5e1; line-height: 1.8;">
                                    Développeur web passionné depuis plus de 3 ans, je me spécialise dans la création 
                                    d'applications web modernes et performantes. Mon expertise couvre le développement 
                                    front-end avec React, le back-end avec Node.js, et le design UI/UX.
                                </p>
                                <p style="margin-bottom: 0; font-size: 1.1rem; color: #cbd5e1; line-height: 1.8;">
                                    J'aime relever des défis techniques et créer des solutions qui améliorent 
                                    l'expérience utilisateur. Toujours en veille technologique, je m'adapte 
                                    rapidement aux nouvelles tendances du développement web.
                                </p>
                            </div>
                            
                            <!-- Stats -->
                            <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1.5rem; margin-bottom: 2rem;">
                                <div style="text-align: center; padding: 1rem; background: rgba(99, 102, 241, 0.1); border-radius: 15px; border: 1px solid rgba(99, 102, 241, 0.2);">
                                    <div style="font-size: 2rem; font-weight: 700; color: var(--accent-color); margin-bottom: 0.5rem;">3+</div>
                                    <div style="font-size: 0.9rem; color: var(--secondary-color);">Années d'expérience</div>
                                </div>
                                <div style="text-align: center; padding: 1rem; background: rgba(236, 72, 153, 0.1); border-radius: 15px; border: 1px solid rgba(236, 72, 153, 0.2);">
                                    <div style="font-size: 2rem; font-weight: 700; color: var(--primary-color); margin-bottom: 0.5rem;">15+</div>
                                    <div style="font-size: 0.9rem; color: var(--secondary-color);">Projets réalisés</div>
                                </div>
                                <div style="text-align: center; padding: 1rem; background: rgba(99, 102, 241, 0.1); border-radius: 15px; border: 1px solid rgba(99, 102, 241, 0.2);">
                                    <div style="font-size: 2rem; font-weight: 700; color: var(--accent-color); margin-bottom: 0.5rem;">10+</div>
                                    <div style="font-size: 0.9rem; color: var(--secondary-color);">Technologies maîtrisées</div>
                                </div>
                            </div>
                            
                            <a href="assets/mon-cv.pdf" style="text-decoration: none;">
                                <button style="background: var(--gradient-accent); color: var(--text-light); border: none; padding: 1.2rem 2.5rem; border-radius: 50px; font-weight: 600; cursor: pointer; transition: var(--transition); box-shadow: 0 8px 20px rgba(99, 102, 241, 0.4); font-size: 1.1rem; display: inline-flex; align-items: center; gap: 0.8rem;">
                                    <i class="fas fa-download"></i> Télécharger mon CV
                                </button>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>