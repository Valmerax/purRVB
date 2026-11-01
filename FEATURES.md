# Liste complète des fonctionnalités / Corrections de bugs

![covers](/box_art/PureRGB_Covers.png?raw=true)

Les seules différences entre RougePur, VertPur et BleuPur sont visuelles. Jouez avec la couleur que vous préférez ! Les 151 Pokémon sont tous obtenables sans échange.

## Nouvelles options dans le menu Options
De nombreuses options ont été ajoutées au menu Options du jeu. Pour être clair, il y a désormais **5 pages d'options**. **Utilisez le bouton Suivant dans le menu Options** pour passer d'une page à l'autre.

Vous pouvez appuyer sur SELECT pour obtenir une explication de l'option sélectionnée dans n'importe quel menu d'options.

La première page contient les options du jeu original. La vitesse du texte dispose désormais d'une option "INSTANT" (Instantané), et l'option "LENT" correspond maintenant à la vitesse "Moyenne" du jeu original. Par défaut, la vitesse est réglée sur "VITE" (Rapide). À part cela, le fonctionnement des options ANIMATION COMBAT et STYLE COMBAT n'a pas changé.

![Options First Page](/screenshots/options_page_1.png?raw=true) 

La deuxième page contient de nouvelles fonctionnalités importantes liées au gameplay général.

![Options Second Page](/screenshots/options_page_2.png?raw=true)
  - La première option, `COLOR` permet de choisir différentes palettes de couleurs pour le jeu. Ces palettes ne s'appliquent que si vous jouez sur un système prenant en charge la couleur, comme la GBC, la GBA, le Super Game Boy, etc. **Attention** : Sur Super Game Boy, après avoir modifié ce paramètre, vous devez sauvegarder et redémarrer le jeu pour appliquer le changement. Sur GBC et GBA, le changement est immédiat.
    - `OG`: Palette de couleurs par défaut. Le jeu utilise les couleurs qu'il aurait normalement affichées sur le système utilisé. Sur GBC et GBA, il s'agit d'une palette bicolore limitée, définie directement dans le jeu. Sur Super Game Boy, ce sont les palettes de couleurs SGB par défaut.
    
    ![Blue Title GBC Default](/screenshots/og_title/blue_title_default_gbc_color.png?raw=true) ![Red Title GBC Default](/screenshots/og_title/red_title_default_gbc_color.png?raw=true) ![Green Title GBC Default](/screenshots/og_title/green_title_default_gbc_color.png?raw=true)
    - `SGB1`: Force l'utilisation des palettes de couleurs Super Game Boy. Sur Super Game Boy, cette option est identique à OG. Sur GBC et GBA, elle permet d'utiliser les mêmes palettes que sur Super Game Boy et active le mode couleurs complètes. Dans ce mode, les animations des attaques sont également colorées sur GBC et GBA, avec quelques autres améliorations visuelles.
  
    ![Blue Title SGB](/screenshots/og_title/blue_title_sgb_colors_on_gbc.png?raw=true) ![Red Title SGB](/screenshots/og_title/red_title_sgb_colors_on_gbc.png?raw=true) ![Green Title SGB](/screenshots/og_title/green_title_sgb_colors_on_gbc.png?raw=true)
    
    ![Attack Color Fire Blast SGB](/screenshots/attack_color_fire_blast.png?raw=true) ![Attack Color Ice Beam SGB](/screenshots/attack_color_ice_beam.png?raw=true) ![Attack Color Solar Beam SGB](/screenshots/attack_color_solarbeam.png?raw=true) ![Attack Color Surf SGB](/screenshots/attack_color_surf.png?raw=true)
    - `SGB2`: Force l'utilisation de variantes des palettes Super Game Boy. Pour accéder à cette option, appuyez sur A lorsque SGB1 est sélectionné dans ce menu.
    Cette option fonctionne comme SGB1, mais avec quelques petites différences de couleurs inspirées de la version japonaise de Pokémon Vert. Le blanc tire davantage vers le vert dans toutes les palettes. Parmi les autres différences, Bourg Palette est violacée au lieu d'être vert clair. Argenta, Lavanville, Céladopole, Safrania et le Plateau Indigo présentent également de légères différences dans leurs couleurs principales par rapport à SGB1.
    À part ces quelques différences de couleurs, les fonctionnalités sont identiques à celles de SGB1.

    ![Blue Title SGB2](/screenshots/og_title/blue_title_sgb2_colors_on_gbc.png?raw=true) ![Red Title SGB2](/screenshots/og_title/red_title_sgb2_colors_on_gbc.png?raw=true) ![Green Title SGB2](/screenshots/og_title/green_title_sgb2_colors_on_gbc.png?raw=true)

    Ci-dessous: Gauche = SGB1, Droite = SGB2

    ![sgb1 sgb2 comparison 1](/screenshots/sgb1_sgb2_comparison_pallet.png?raw=true) ![sgb1 sgb2 comparison 2](/screenshots/sgb1_sgb2_comparison_pewter.png?raw=true) ![sgb1 sgb2 comparison 3](/screenshots/sgb1_sgb2_comparison_lavender.png?raw=true) ![sgb1 sgb2 comparison 4](/screenshots/sgb1_sgb2_comparison_saffron.png?raw=true)  ![sgb1 sgb2 comparison 5](/screenshots/sgb1_sgb2_comparison_indigo.png?raw=true)
    - `J1 ou J2`: Force l'utilisation des palettes de couleurs GBC. Sur Super Game Boy, les palettes seront désormais celles de Pokémon Jaune sur GBC, avec leurs couleurs plus intenses. Il en va de même sur GBC et GBA. Sur ces deux dernières consoles, cette option active le mode couleurs complètes. Les animations des attaques sont également colorées dans ce mode, avec quelques autres améliorations visuelles.
    J1 utilise les palettes originales de Pokémon Jaune. J2 utilise les mêmes couleurs que J1, mais avec une intensité réduite, afin de reproduire l'apparence de l'écran d'une véritable Game Boy Color lorsque vous jouez sur un émulateur.
    
    ![Blue Title GBC](/screenshots/og_title/blue_title_gbc_colors_on_gbc.png?raw=true) ![Red Title GBC](/screenshots/og_title/red_title_gbc_colors_on_gbc.png?raw=true) ![Green Title GBC](/screenshots/og_title/green_title_gbc_colors_on_gbc.png?raw=true)

    ![Blue Title GBC2](/screenshots/og_title/blue_title_y2_colors_on_gbc.png?raw=true) ![Red Title GBC2](/screenshots/og_title/red_title_y2_colors_on_gbc.png?raw=true) ![Green Title GBC2](/screenshots/og_title/green_title_y2_colors_on_gbc.png?raw=true)
  - La deuxième option, `COLORIS PKMN ALT`, permet d'activer ou de désactiver les palettes de couleurs alternatives des Pokémon (désactivée par défaut).
  Lorsqu'elle est activée, les fonctionnalités liées aux couleurs alternatives sont disponibles. Dans certaines zones, vous pourrez rencontrer des Pokémon aux couleurs différentes, comme des Nidorino bleus ou des Nidorina violettes. Considérez-les comme des variantes régionales de couleur.
  Cette fonctionnalité est présente pour le plaisir, elle ajoute une raison supplémentaire d'explorer différents endroits à la recherche de Pokémon uniques.

![Alt Colors Off](/screenshots/alt_pokemon_colors_off.png?raw=true) ![Alt Colors On](/screenshots/alt_pokemon_colors_on.png?raw=true)
  - La troisième option, `MUSIQUE` permet d'activer ou de désactiver de nouveaux morceaux de musique (défaut: OG). Réglez-la sur OG+ pour entendre les nouveaux morceaux aux moments prévus. Pour l'instant, cette option ne concerne qu'un ou deux morceaux secondaires, notamment le thème de Giovanni, issu de musiques inutilisées dans le code de Pokémon Jaune. D'autres morceaux seront probablement ajoutés à l'avenir.
  - La quatrième option, `PAN AUDIO` permet d'activer ou de désactiver la spatialisation stéréo du son (défaut : OFF). Le jeu utilise déjà un son stéréo, mais chaque canal est diffusé au même volume dans les haut-parleurs gauche et droit, ce qui donne une impression de son mono. Lorsque cette option est activée, la musique devient un peu plus dynamique grâce à la répartition de certains canaux entre la gauche et la droite.
  Cette option existait dans Pokémon Jaune et a été intégrée à ce ROM hack.
  - La cinquième option, `SON VELO` permet d'activer ou de désactiver la musique jouée à vélo (défaut : ON).
  Comme cette musique est jouée pendant toute la durée des déplacements à vélo, elle peut devenir lassante à la longue. Si vous la désactivez, vous ne l'entendrez plus que sur la Piste Cyclable.
  Vous pourrez ainsi profiter de toutes les musiques du jeu, et pas uniquement de celle du vélo.
  - La sixième option, `FONDU GBC` permet d'activer ou de désactiver des transitions en fondu plus fluides sur GBC (défaut : OFF).
  Les animations de fondu seront beaucoup plus fluides, notamment lorsque vous entrez dans un bâtiment ou que vous vous envolez vers une autre ville. Cette fonctionnalité ne fonctionne que sur GBC.

La troisième page contient des paramètres liés aux combats. 

![Options Third Page](/screenshots/options_page_3.png?raw=true)
-
  - Les quatre premières options, `SPE→PSY`, `GLA→FEU`, `INS→PSN`, `PSN→INS` contrôlent les relations entre les types. Pour chacune d'elles, le réglage de gauche correspond à la table des types du jeu original, tandis que celui de droite correspond à la modification apportée dans la deuxième génération. Ces options vous permettent d'ajuster les relations entre les types selon vos préférences. La seule exception au comportement original concerne SPE→PSY, qui est réglée par défaut pour que le type Spectre soit très efficace contre le type Psy. Dans le jeu original, les Pokémon Psy étaient immunisés aux attaques Spectre, alors même que certains dialogues de PNJ indiquaient que cela ne devrait pas être le cas.
  - La cinquième option, `BAR EXP` active ou désactive une barre d'expérience visuelle en combat (défaut : OFF). Cette fonctionnalité facilite le suivi de l'expérience gagnée en combat.
  
   ![Exp bar](screenshots/exp_bar.png?raw=true)
  - La sixième option, `PNJ EV` active ou de désactive l'attribution de Stat EXP. aux Pokémon des Dresseurs adverses, en fonction de leur niveau (défaut : OFF). Dans le jeu original, les Pokémon adverses ne recevaient aucun Stat Exp., quel que soit leur niveau. Ainsi, si vos Pokémon avaient accumulé beaucoup de Stat Exp., ils pouvaient largement surpasser les Pokémon de Dresseurs de niveau similaire.
  Lorsque cette option est activée, les Pokémon des Dresseurs reçoivent une quantité raisonnable de Stat Exp. proportionnelle à leur niveau. Le jeu devient alors un peu plus difficile, mais cette option peut être intéressante pour les joueurs expérimentés.
  - La septième option, `PNJ PP` active ou désactive le suivi des PP des Pokémon adverses (défaut : OFF). Dans le jeu original, les adversaires disposaient de PP illimités pour leurs attaques. Si cette option est activée, ils peuvent épuiser leurs PP en utilisant certaines attaques trop souvent.
  Cela rend les combats un peu plus faciles, notamment vers la fin du jeu, lorsque les attaques de soin deviennent plus fréquentes.

La quatrième page contient des options liées aux sprites.
 
![Options Fourth Page](/screenshots/options_page_4.png?raw=true)
  - The first option, `DOS` changes the back sprites in the game. (Default: OG) There are two possible settings:
    - OG: Utilise les sprites de dos originaux pixelisés.
    
    ![Original back sprite venusaur](/gfx/pokemon/back/venusaurb.png?raw=true) ![Original back sprite blastoise](/gfx/pokemon/back/blastoiseb.png?raw=true) ![Original back sprite charizard](/gfx/pokemon/back/charizardb.png?raw=true)
    - SW97: Utilise les sprites de dos Spaceworld 1997 (certains ont été légèrement retouchés). Leur résolution est supérieure tout en respectant le style graphique du jeu original. Très joli !
    
    ![Spaceworld back sprite venusaur](/gfx/pokemon/back_sw/venusaurb.png?raw=true) ![Spaceworld back sprite blastoise](/gfx/pokemon/back_sw/blastoiseb.png?raw=true) ![Spaceworld back sprite charizard](/gfx/pokemon/back_sw/charizardb.png?raw=true)
  - La deuxième option, `ICONES` change les icônes des menus et les sprites de l'univers du jeu (défaut : OG). There are two possible settings:
    - OG: Utilise les icônes originales dans le monde et dans le menu Pokémon.
    - OG+: Utilise les icônes originales auxquelles s'ajoutent de nouvelles icônes. Certaines sont inspirées des sprites bêta, tandis que d'autres ont été entièrement créées pour rester fidèles au style des icônes originales, volontairement peu détaillées. Une icône est également inspirée des sprites de menu de la deuxième génération (sprite méduse). Cette option ajoute aussi des sprites uniques pour Pierre, Ondine, Major Bob, Erika, Morgane et Auguste. Tous ont été créés de zéro pour correspondre aux sprites de Dresseurs originaux du jeu, à l'exception de celui d'Auguste, repris de la deuxième génération.

 ![Menu Icons 1](/gfx/icons/menusprites1.png?raw=true) ![Menu Icons 2](/gfx/icons/menusprites2.png?raw=true)
    ![Brock](/gfx/sprites/brock.png?raw=true) ![Misty](/gfx/sprites/misty.png?raw=true) ![LtSurge](/gfx/sprites/lt_surge.png?raw=true) ![Erika](/gfx/sprites/erika.png?raw=true) ![Sabrina](/gfx/sprites/sabrina.png?raw=true) ![Blaine](/gfx/sprites/blaine.png?raw=true)
  - Si vous appuyez sur A sur `MOD.` de la troisième option, cinq nouvelles pages s'ouvriront dans un sous-menu. Elles permettent de personnaliser les sprites de face des Pokémon.
  Vous pouvez appuyer sur A ou SELECT pour afficher un aperçu du sprite de face choisi pour chaque option.

![Front Sprite Options 1](/screenshots/front_sprite_options1.png?raw=true)
![Front Sprite Options 2](/screenshots/front_sprite_options2.png?raw=true)
![Front Sprite Options 3](/screenshots/front_sprite_options3.png?raw=true)
![Front Sprite Options 4](/screenshots/front_sprite_options4.png?raw=true)
![Front Sprite Options 4](/screenshots/front_sprite_options5.png?raw=true)

  Vous pouvez personnaliser les sprites suivants:

![front_sprite_options](/gfx/pokemon/gallery/front_sprite_options.png?raw=true)

La cinquième page contient plusieurs options supplémentaires.

![Options Fifth Page](/screenshots/options_page_5.png?raw=true)
- Activer ou désactiver la pause/reprise de la musique entre les combats. Si vous ne voulez pas que la musique d'une route ou d'une grotte recommence depuis le début après chaque combat contre un Pokémon sauvage que vous fuyez, désactivez cette option. La musique de la zone sera alors mise en pause puis reprise.
- Activer ou désactiver la fonctionnalité d'apprentissage des capacités. Elle est activée par défaut. Lorsque cette fonctionnalité est active, vous pouvez débloquer les listes de capacités des Pokémon de différentes manières, comme expliqué dans la section "Nouvelles fonctionnalités".
- Activer le nouvel écran-titre créé pour PurRVB. Par défaut, le jeu affiche l'écran-titre original correspondant à la version à laquelle vous jouez.
  
![Pure Red Title](/screenshots/pure_red_title0.png?raw=true)![Pure Green Title](/screenshots/pure_green_title0.png?raw=true)![Pure Blue Title](/screenshots/pure_blue_title0.png?raw=true)
- Vous pouvez passer l'introduction au démarrage du jeu pour accéder directement à l'écran-titre.
- Vous pouvez réduire l'intensité des effets de clignotement pendant les combats.
- Vous pouvez choisir entre les unités impériales et métriques utilisées dans les informations du Pokédex.

## Améliorations de confort de jeu
- Les évolutions par pierre et par échange disposent d'un moveset complet.
- Les Pokémon évoluant par échange évoluent au niveau 37.
- Les déplacements dans le monde extérieur sont plus fluides.
- Toutes les CT enseignent des attaques utiles.
- Les capacités apprises en montant de niveau ont été largement améliorées pour tous les Pokémon.
- La capacité du sac passe de 20 à 30 objets.
- La capacité de stockage d'objets du PC passe de 50 à 60.
- Depuis le menu des objets, vous pouvez déposer un objet directement dans le PC en appuyant sur START. La technologie est incroyable ! Le stockage sans fil est désormais possible !

![Deposit Item From Start Menu](/screenshots/deposit_item_from_menu.png?raw=true)
- Ouvrez le menu START et défiler jusqu'à SAVE, puis appuyez sur SELECT pour changer de boîte PC à tout moment et n'importe où. Le menu de changement de boîte a également été amélioré pour inclure le nombre de Pokémon dans chaque boîte.

![Box change](/screenshots/change_box_from_start_menu.png?raw=true)
- Lorsque vous consultez le PC de Léo, le nombre de Pokémon dans la boîte actuelle est toujours affiché.
- Le PC de Léo et celui du joueur sont plus réactifs et leurs menus se ferment moins souvent intempestivement.
- Après avoir capturé un Pokémon, le jeu indique le nombre de places restantes dans la boîte, ainsi que lorsque celle-ci est pleine.
- Lorsque vous sélectionnez une CT ou une CS dans un menu, une fenêtre affiche automatiquement la capacité enseignée. Hourra !

![TM Text](/screenshots/tm_text_box_prompt.png?raw=true)
- Dans toutes les listes défilantes (menu des objets, menus du PC, ascenseurs, etc.), appuyez sur GAUCHE de la croix directionnelle pour passer directement du début à la fin de la liste, et inversement. Très pratique !
- Lors de l'achat ou de la vente d'objets, vous pouvez augmenter ou diminuer la quantité par paliers de 10 en appuyant sur GAUCHE ou DROITE.
- La plupart des menus mémorisent mieux votre position dans les listes après certaines actions.
- Après une partie de pêche, le jeu se souvient que vous venez d'utiliser une canne à pêche et conserve la position du menu pour faciliter sa réutilisation.
- Le Cherch'Objet vous oriente vers l'objet lorsqu'il y en a un à proximité.
- L'alarme de faible santé retentit trois fois, puis s'arrête au lieu de sonner sans interruption pendant les combats.
- La vitesse de sauvegarde a été augmentée.
- TÉLÉPORT est utilisable dans les grottes et les bâtiments.
- Un objet permettant d'utiliser TÉLÉPORT sans avoir de Pokémon connaissant cette capacité dans son équipe a été ajouté. Vous pouvez l'obtenir à Argenta.
- Appuyez sur SELECT dans le monde extérieur pour utiliser le vélo s'il se trouve dans votre sac. Après avoir vu une fois les messages "Vous enfourchez votre vélo" et "Vous descendez de votre vélo", monter et descendre du vélo devient instantané.
- Maintenez B pour courir. Maintenez B à vélo pour accélérer. La vitesse de l'animation s'adapte également à votre déplacement.
- Le vélo peut être utilisé à l'intérieur des postes de garde.
- Arrêtez-vous, puis maintenez simultanément B et A. Vous pouvez alors changer de direction sans vous déplacer.
- VOL est utilisable dans certains lieux où il aurait dû l'être, mais ne fonctionnait pas (Forêt de Jade, Parc Safari, toit du Centre Commercial de Céladopole et toit du Manoir de Céladopole).
- Le Maître des Noms accepte désormais toujours de renommer vos Pokémon, même ceux obtenus par échange. Il s'attendrit ?
- Lors du choix d'une destination avec VOL, les délais inutiles entre chaque sélection ont été supprimés.
- Le jeu affiche désormais toujours le bon message ("C'est très efficace !", "Ce n'est pas très efficace...", etc.) pendant les combats. Fini les astuces !
- Les CS peuvent être oubliées. Du code empêche tout blocage définitif si vous les oubliez au mauvais endroit.
- Lorsqu'une capacité est enseignée avec une CT, il y a moins de texte à faire défiler.
- Lorsqu'un Pokémon essaie d'apprendre une nouvelle capacité, vous pouvez ignorer définitivement la question "X connaît déjà 4 capacités. En oublier une pour en apprendre une nouvelle ?" en sélectionnant "CACHER" plutôt que "OUI" ou "NON".
- Lorsque vous enseignez une capacité à un Pokémon et choisissez celle à oublier, vous devez appuyer sur START plutôt que sur A pour valider votre choix. Cela évite les erreurs catastrophiques !
- Pour relâcher un Pokémon, vous devez appuyer sur START pour confirmer. Cela évite les relâchements accidentels.
- Les cases tournantes du Repaire Rocket et de l'Arène de Jadielle vous déplacent beaucoup plus rapidement.
- Le menu "Utiliser un autre Repousse ?" a été ajouté.
- De nouvelles informations dans le Pokédex : le type des Pokémon aperçus est affiché, ainsi que le type et les statistiques de base des Pokémon capturés.

![Pokedex Base Stats](/screenshots/pokedex_base_stats_typing.png?raw=true)
- Appuyez sur SELECT dans le Pokédex pour afficher le sprite de dos des Pokémon capturés lorsque vous consultez leur fiche.
- Lors du quiz de l'Arène de Cramois'Île, les explications ne sont plus répétées à chaque fois que vous le lancez.
- La Boîte Jetons ne prend plus de place dans votre sac. Rendez-vous au Casino pour consulter votre nombre de jetons.
- Les objets Clé Secrète, Carte Magnétique et Clé Ascenseur sont automatiquement consommés lorsqu'ils ne sont plus nécessaires. Moins d'encombrement !
- Après que vous avez aidé le capitaine de l'Océane, celui-ci veille à ce que vous n'ayez plus besoin du Ticket Bateau pour accéder à la zone de l'Océane.
- Après avoir sauvé M. Fuji, une Exorciste au deuxième étage de la Tour Pokémon vous propose de lui confier votre Scope Sylphe. Elle vous le rendra sur demande. Vous pouvez ainsi le laisser là pour libérer de la place dans votre sac ou votre PC.
- La Carte ne prend plus de place dans votre sac. Pour la consulter, ouvrez le Pokédex et appuyez sur SELECT. (Vous devez tout de même l'obtenir à Bourg Palette pour débloquer cette fonctionnalité.)
- L'animation de pêche est globalement un peu plus courte.
- La pêche permet désormais d'obtenir un Pokémon avec un taux fixe de 75 %.
- Vous pouvez acheter des boissons en quantité au Diner de Céladopole après en avoir donné une à l'un des gardes de Safrania.
- Vous pouvez acheter 500 jetons pour 8 000 Pokédollars au Casino, autant de fois que vous le souhaitez.
- Les machines à sous ne vous empêchent plus d'aligner des symboles en fonction du générateur aléatoire.
- Les gains des machines à sous ont été augmentés.
- Les gains des machines à sous sont distribués plus rapidement.
- Après avoir utilisé SURF, le jeu mémorise la capacité jusqu'au prochain chargement de carte. Vous pouvez simplement marcher sur l'eau pour surfer, sans action supplémentaire ni même appuyer sur A.
- Vous pouvez utiliser FORCE sur un rocher en appuyant sur A si un Pokémon connaissant cette capacité se trouve dans votre équipe.
- Les Îles Écume et la Route Victoire mémorisent l'utilisation de FORCE lorsque vous changez d'étage. Vous n'avez donc pas besoin de réactiver la capacité.
- Les Îles Écume, la Caverne Azurée et le Parc Safari mémorisent l'utilisation de SURF lorsque vous passez d'une zone à l'autre. Plus besoin de l'utiliser à répétition.
- Le plan de Parmanie a été légèrement modifié pour rendre les déplacements moins pénibles.
- La Pension dispose désormais d'un PC.
- Un peu d'herbe a été ajoutée sur la Route 23, juste après la sortie nord de la Route Victoire, pour faciliter l'accès aux Pokémon sauvages en fin de jeu. Les Pokémon qui s'y trouvent donnent leur EXP complète, contrairement aux autres Pokémon sauvages : c'est donc un bon endroit pour s'entraîner.
- Les ascenseurs indiquent désormais lorsque vous sélectionnez l'étage où vous vous trouvez déjà.
- Certains Pokémon évoluent à des niveaux plus bas.
- Les statistiques de base de nombreux Pokémon ont été améliorées. Vous pouvez les consulter dans leur fiche du Pokédex après les avoir capturés, ou retrouver toutes les données sur le wiki.
- Les capacités apprises par de nombreux Pokémon ont été améliorées. Consultez le wiki pour les détails.
- Vous pouvez désormais utiliser le Cherch'Objet au CASINO pour détecter les jetons cachés.
- Un outil de mise à jour des sauvegardes a été ajouté. Il permet de transférer votre sauvegarde du jeu original pour l'utiliser avec PurRVB. Ouvrez simplement votre ancienne sauvegarde dans PurRVB : le jeu vous proposera de la mettre à jour.
- Appuyez sur SELECT lorsque l'option RETIRER est sélectionnée dans le PC pour consulter les Pokémon de la boîte, même si votre équipe est complète.
- Appuyez sur SELECT lorsque vous consultez les statistiques d'un Pokémon pour afficher ses points d'expérience statistiques pour chaque caractéristique.
- Vous pouvez réorganiser les Pokémon de votre équipe dans le menu de l'équipe en appuyant sur SELECT, comme pour déplacer des objets ou des capacités.
- Lorsque vous consultez votre sac ou les objets du PC, le nombre d'emplacements utilisés et disponibles est affiché : 15/30, 20/60.
- MAXI REPousse empêche totalement les rencontres avec les Pokémon sauvages tant qu'il est actif.
- L'optimisation du code d'affichage du texte accélère et fluidifie la navigation dans les menus à listes.
- Le compteur de temps de jeu peut désormais dépasser 255 heures, jusqu'à plus de 10 000 heures !
- Le délai artificiellement long lors de l'échange d'objets dans le menu du sac a été réduit.
- Le menu principal (CONTINUER / NOUVELLE PARTIE / OPTIONS) est plus rapide et réactif.
- Dans les menus des ascenseurs, l'étage actuel est désormais indiqué.
- Vous pouvez donner des noms personnalisés de cinq lettres aux boîtes du PC.
- Appuyez sur SELECT lorsque l'option "OBJET" est sélectionnée dans le menu START pour trier automatiquement les objets de votre sac.
- Appuyez sur SELECT lorsque vous consultez le "PC du joueur" pour trier automatiquement les objets stockés dans le PC.
- Le répertoire du Centre Commercial de Céladopole utilise désormais un menu, plus simple à parcourir. La vendeuse du rez-de-chaussée vous donnera également les mêmes informations à sa manière.
- Si vous reparlez à l'infirmière du Centre Pokémon après avoir soigné votre équipe, son dialogue ne se déclenchera plus tant que vous n'aurez pas quitté sa position. Cela évite de relancer accidentellement son dialogue.
- Une fenêtre d'information "Pokémon sélectionné" a été ajoutée aux menus RETIRER / DÉPOSER / RELÂCHER du PC. Elle affiche le nom de l'espèce, l'icône de l'équipe et les types du Pokémon. Vous pouvez ainsi lui donner un surnom sans oublier de quel Pokémon il s'agit.
- La fonction de chargement des graphismes des décors a été optimisée : de nombreux écrans se chargent deux fois plus vite qu'avant, notamment le menu START, les dialogues avec les PNJ et le menu de l'équipe.
- Lorsque vous utilisez des objets sur votre équipe, le menu reste ouvert tant qu'il vous reste des objets utilisables. Par exemple, si vous avez plusieurs Super Bonbons, inutile de rouvrir le menu de l'équipe à chaque utilisation.
- De petits messages dans les menus START et PC indiquent les actions spéciales accessibles avec SELECT : changer de boîte depuis le menu START, trier les objets du sac, consulter le contenu d'une boîte depuis le menu PC et trier les objets du PC du joueur.

## Nouvelles fonctionnalités de jeu
- Mew se trouve sous le camion !!! Utilisez FORCE sur lui depuis le côté droit. Si l'Océane est déjà partie, elle revient après l'obtention du Badge Âme.
- MissingNo. et le glitch de duplication d'objets sont toujours accessibles. MissingNo. peut être capturé sans corrompre vos données de jeu. Il est très puissant, alors soyez prudent en essayant de le capturer ! MissingNo. affiche également aléatoirement différents sprites à chaque chargement : son sprite "glitché" d'origine, celui du Spectre ou le fossiles de Kabutops/Ptéra.

 ![Missingno](/screenshots/missingno.png?raw=true)

- Un tout nouveau mode de Pokédex a été ajouté : le CAPADEX. Il répertorie toutes les capacités dont vous avez vu l'animation en combat et affiche leurs informations et caractéristiques détaillées. Essayez de compléter votre CAPADEX ! Il est accessible dans une nouvelle salle de classe au sous-sol de l'école de Jadielle. Vous pouvez passer du classement par ID au classement alphabétique avec SELECT lorsque vous consultez le CAPADEX.

![movedex](/screenshots/movedex.png?raw=true) ![movedex thunderbolt](/screenshots/movedex_thunderbolt.png?raw=true) ![movedex flamethrower](/screenshots/movedex_flamethrower.png?raw=true) ![movedex surf](/screenshots/movedex_surf.png?raw=true) ![movedex eq](/screenshots/movedex_earthquake.png?raw=true)

- Un AUTRE tout nouveau mode de Pokédex a été ajouté : la consultation des capacités apprises ! Il affiche les capacités apprises par montée de niveau, celles apprises par CT et les évolutions d'un Pokémon. Vous pouvez débloquer ces informations après avoir obtenu le CAPADEX, en parlant à des personnes connaissant certains Pokémon, en lisant des livres à leur sujet ou simplement en entraînant suffisamment vos Pokémon pour devenir vous-même un expert.

![learnset 1](/screenshots/learnset_1.png?raw=true) ![learnset_2](/screenshots/learnset_2.png?raw=true) ![learnset_3](/screenshots/learnset_3.png?raw=true)

- ENCORE un nouveau mode de Pokédex a été ajouté : consultez la répartition des Pokémon sauvages en sélectionnant des zones sur la Carte. Vous pouvez même choisir des étages précis dans les donjons à plusieurs niveaux ! Débloquez cette fonctionnalité en capturant 50 Pokémon, puis en parlant à l'ASSISTANT dans le bâtiment de réunion de PARMANIE.

![town map wild data](/screenshots/town_map_wild_data.png?raw=true)
 
- Ossatueur Spectre peut être capturé. Si l'option Palette Pkmn Alt est activée, il possède une coloration spectrale spéciale. Il veut se venger de la Team Rocket ! M. Fuji réagira différemment à son sauvetage si vous l'avez capturé.

- Le Parc Safari propose désormais trois modes de jeu différents :
  - `CLASSIQUE` : le mode Safari du jeu original. Utilisez des appâts et des pierres plutôt que vos Pokémon entraînés pour tenter de capturer des Pokémon sauvages avec des Safari Balls. Seule différence : vous disposez de 700 pas au lieu de 500.
  - `CHASSE AU RANGER` : trouvez les 5 rangers et battez-les avant d'épuiser vos pas pour obtenir un prix spécial ! Comme en mode FREE ROAM, vous pouvez emmener vos Pokémon, mais vous ne disposez que de 700 pas pour trouver et vaincre les 5 rangers. Tous les dresseurs du mode FREE ROAM sont également présents. C'est le défi ultime du Parc Safari ! La récompense est une nouvelle Poké Ball : l'HYPER BALL, qui capture à coup sûr les Pokémon ayant moins d'un tiers de leurs PV. Même les Pokémon légendaires ! Ce défi peut être recommencé.
  - `EXPLORATION LIBRE` : emmenez vos Pokémon dans le Parc Safari et capturez ou combattez des Pokémon comme à l'habitude. Il n'y a aucune limite de pas ! Des dresseurs sont également présents dans tout le parc. Ils réapparaissent lorsque vous entrez à nouveau, ce qui permet de les affronter plusieurs fois.
  
   ![Safari Zone Modes](/screenshots/safari_zone_modes.png?raw=true) ![Safari Zone Trainers](/screenshots/safari_zone_ranger_hunt.png?raw=true) 

- Nouveaux objets :
  - `ABRA POCKET` : Un Abra qui tient dans votre sac. Un Pokémon de poche ! Un peu redondant, non ?... Il permet d'utiliser TELEPORT à tout moment, même dans les bâtiments et les grottes, pour retourner au dernier Centre Pokémon visité. Gardez-le toujours sur vous ! Vous pouvez même lui donner un surnom.
  - `PUCE EXP` : Remplace `MULTI EXP`. L'assistant du Professeur Chen sur la Route 15 vous la donnera si vous avez capturé au moins 80 Pokémon. Une fois installée sur votre ceinture à Poké Balls, elle augmente l'EXP gagnée par tous vos Pokémon, comme s'ils avaient été obtenus par échange. Idéal pour entraîner votre équipe tout en complétant le Pokédex.
  - `PUCE APEX` : Une invention du Guide des Arènes ! Une fois installée, elle maximise les DVs (aussi appelés IVs). Le Guide des Arènes vous en donnera deux après chaque victoire contre un Champion d'Arène. Installée dans la Poké Ball d'un Pokémon, cette puce simule son habitat naturel pour le rendre heureux et lui permettre d'atteindre son plein potentiel ! L'écran des statistiques indique également si ses DVs sont au maximum.
  - `HYPER BALL` : Comme expliqué précédemment, une nouvelle Poké Ball qui capture à coup sûr les Pokémon ayant moins d'un tiers de leurs PV. Pour de nombreux Pokémon non légendaires, elle fonctionne même avec leurs PV au maximum ! Gardez-les de préférence pour les Pokémon légendaires : elles sont assez rares.

- Une toute nouvelle zone a été ajoutée au Plateau Indigo. Après être devenu Maître, parlez à la femme en haut à gauche du hall du Plateau Indigo pour accéder à l'Arène des Champions. Vous pourrez y affronter à nouveau tous les Champions d'Arène et les membres du Conseil 4, avec quelques animations et séquences spéciales. Les adversaires ont des IV parfaits : pensez donc à équiper toute votre équipe de PUCE APEX ! Ils disposent également de sets de capacités personnalisés et du niveau d'IA le plus élevé. Préparez-vous ! Vous pouvez choisir parmi plusieurs pistes audio pour accompagner les combats. Au début, les adversaires sont affrontés dans un ordre prédéfini. Une fois tous vaincus, vous pourrez choisir qui affronter. Ils seront encore plus puissants lors de la deuxième confrontation !

   ![Champ Arena](/screenshots/champ_arena.png?raw=true)

- Le "Pirate CT" est un GAMIN que l'on trouve dans la plupart des boutiques Pokémon. Il vous vend des CT ! Une façon amusante d'ajouter davantage de CT à acheter dans le jeu.

- Une nouvelle zone inspirée des données préliminaires du "donjon de Sulfura" a été ajoutée sur la route maritime entre Bourg Palette et la Cramois'Île : le Volcan Cramois'Île ! Vous pouvez y capturer Sulfura plus tôt dans le jeu. Vous pouvez aussi désactiver entièrement cette zone si vous ne souhaitez pas y accéder : rendez-vous sur votre PC et désactivez-la dans le menu OPTIONS MONDE. Explorez ce nouveau volcan et ses nombreux éléments visuels inédits. Vous pouvez également y améliorer votre MAGMAR grâce à la puissance du volcan !

![volcano](/screenshots/volcano.png?raw=true) ![world options](/screenshots/world_options.png?raw=true)

- La Centrale a été améliorée visuellement avec les graphismes bêta de Spaceworld 1997. Elle propose désormais un petit puzzle supplémentaire : vous devez actionner plusieurs interrupteurs pour déverrouiller des barrières électriques et atteindre la fin de la zone. Elle comprend également un toit et une zone secrète où votre MAGNETON peut être amélioré !

![power plant](/screenshots/power_plant.png?raw=true) ![power plant2](/screenshots/power_plant2.png?raw=true)

- À AZURIA, vous trouverez la DESIGNER DE POKÉ BALLS ! Cette femme crée l'apparence de toutes les Poké Balls pour la SYLPHE SARL. Devenez son assistant et prenez des photos de choses intéressantes avec son APP. PHOTO, afin de lui inspirer de nouvelles Poké Balls aux effets audiovisuels spéciaux !
Changez les Poké Balls de vos Pokémon ! PERSONNALISEZ 16 DE VOS PROPRES POKÉ BALLS AVEC DES NOMS PERSONNALISÉS, 16 ANIMATIONS D'APPARITION PERSONNALISABLES, 16 ANIMATIONS DE LANCER PERSONNALISABLES, 16 PALETTES DE COULEURS PERSONNALISABLES, 16 EFFETS SONORES PERSONNALISABLES ET 16 TYPES DE MOTIF D'ANIMATION PERSONNALISABLES !!
Les Poké Balls n'ont jamais été aussi personnalisables ! DEVENEZ DESIGNER DE POKÉ BALLS !

![ball designer 1](/screenshots/ball_designer1.png?raw=true) ![ball designer 2](/screenshots/ball_designer2.png?raw=true)![ball designer 3](/screenshots/ball_designer3.png?raw=true) ![ball designer 4](/screenshots/ball_designer4.png?raw=true)

- La légende urbaine — le jardin de Bill — a été ajoutée au jeu ! Il n'est accessible qu'une fois devenu Maître. Vous y trouverez des choses amusantes. Allez-y plusieurs fois ! Ce que vous y trouverez peut changer ! Si les palettes alternatives sont activées dans les options... est-ce un Pikachu bleu ??

![bills garden](/screenshots/bills_garden.png?raw=true)

- L'INTELLO des fossiles du Mont Sélénite vous proposera d'apporter immédiatement votre fossile au laboratoire de la Cramois'Île ! Si vous lui confiez votre fossile, vous devrez le retrouver chez lui à SAFRANIA pour récupérer votre Pokémon fossile. Vous pourrez ensuite lui confier aussi le VIEIL AMBRE. Cela permet d'obtenir des Pokémon fossiles plus tôt dans l'aventure.

![Super Nerd House in Saffron](/screenshots/super_nerd_in_saffron_city.png?raw=true)
- Vous pouvez trouver le fossile que vous n'avez pas choisi au Mont Sélénite, caché dans les Îles Écume.

- NICO et JULIA sont des personnages du jeu original qui se cherchaient à Parmanie. Aidez-les à se retrouver pour découvrir leur histoire, puis rendez visite à leur maison sur la route maritime au sud de Parmanie (Route 19) ! Améliorez votre DRACO en suivant leur aventure de plongée sous-marine. Cette maison sur la Route 19 s'inspire d'un contenu bêta montrant une maison sur une île de la Route 21.

![erik and sara](/screenshots/erik_and_sara.png?raw=true)

- À Céladopole, un PNJ de l'hôtel vous donnera un LOKHLASS avant l'heure après avoir terminé le Repaire Rocket. C'est le même homme qui vous le donne à la Sylphe SARL lors d'un voyage d'affaires. Comme prévu, il se retrouvera ensuite coincé à la Sylphe SARL ! Si vous ne récupérez pas LOKHLASS à l'avance, vous pourrez toujours l'obtenir de la manière originale.

- À Parmanie, un PNJ peut supprimer définitivement les arbres COUPE contre rémunération. Faites retirer tous les arbres de Parmanie, celui qui bloque la Route 9, et bien d'autres !

![Tree Deleter](/screenshots/tree_deleter.png?raw=true)
- Si l'option Palette Pkmn Alt est activée, un PNJ du laboratoire de Cramois'Île vous permettra d'échanger la palette de couleurs de vos Pokémon contre leur palette alternative. Le nombre de changements de couleur est limité !

 ![Lab color changer NPC](/screenshots/color_changer_npc.png?raw=true)

- Après le premier garde du Plateau Indigo, vous trouverez une porte menant à la maison d'un homme qui habite sur la Route 23. Il peut rétablir les types d'origine des Pokémon si vous le souhaitez. Vous pouvez choisir précisément quels Pokémon conservent leurs nouveaux types ou retrouvent leurs types d'origine.

 ![Type Guys House](/screenshots/type_guys_house.png?raw=true)
 
- Une nouvelle zone a été ajoutée au sous-sol de l'école de Jadielle. Elle sert de zone d'aide en début de jeu, avec davantage d'informations sur les bases du jeu : statistiques, efficacité des types, STAB, etc. C'est également là que vous débloquerez le CAPADEX.

![schoolhouse basement](/screenshots/new_school_basement.png?raw=true)

- Le MAITRE PECHEUR habite désormais à Azuria, ce qui permet d'obtenir la CANNE un peu plus tôt. Même chose pour la SUPER CANNE, désormais disponible dans la maison de l'ancien MAITRE PECHEUR à Carmin sur Mer. Quant aux deux derniers maîtres, sur la Route 12 et à Parmanie, le premier que vous rencontrerez vous donnera une MEGA CANNE. L'autre sera un peu décontenancé par ce retournement de situation, puis vous donnera un GUIDE DE PECHE. Celui-ci débloque l'affichage des lieux de pêche des Pokémon dans le Pokédex.

![Fishing locations good rod](/screenshots/areas_good_rod.png?raw=true) ![Fishing Locations old rod](/screenshots/areas_old_rod.png?raw=true) ![Fishing locations super rod](/screenshots/areas_super_rod.png?raw=true)

- Vous pouvez téléphoner chez vous, au Professeur Chen, et même à votre rival depuis les téléphones du Centre Commercial de Céladopole. Vous pouvez choisir le déroulement des conversations, et certains de vos choix pourront même déclencher de petits événements par la suite, lorsque vous retournerez à BOURG PALETTE !

![phone tree 1](/screenshots/phone1.png?raw=true)
![phone tree 2](/screenshots/phone2.png?raw=true)

- Après avoir sauvé M. Fuji dans la Tour Pokémon, vous pourrez accéder au sous-sol de la tour. Vous y trouverez une exorciste vêtue de noir qui adore les malédictions, les sortilèges et tout ce qui touche aux arts obscurs. Si vous lui montrez un ECTOPLASMA, elle lui lancera une malédiction pour lui redonner l'apparence d'un SPECTRUM. Ses statistiques ne seront toutefois pas affectées, il conservera celles d'ECTOPLASMA. Quelle malédiction puissante !

![dark channeler](/screenshots/dark_channeler.png?raw=true)

- Après avoir vaincu GIOVANNI à l'ARÈNE DE JADIELLE, si vous avez capturé le fantôme d'OSSATUEUR, vous pourrez lui permettre de reposer en paix dans le sous-sol de la Tour Pokémon ! Une touchante réunion avec un OSSELAIT, et quelques esprits Pokémon effrayants à combattre en chemin.

![ghost marowak area](/screenshots/ghost_marowak_area.png?raw=true)

- Sur la Route 8, vous trouverez une nouvelle petite grotte où un prospecteur creuse pour trouver des diamants. Aidez-le et il renforcera votre ONIX. Ses statistiques de base seront augmentées et il subira moins de dégâts des capacités de type EAU, GLACE et PLANTE.

![diamond mine](/screenshots/diamond_mine.png?raw=true)

- Après avoir aidé le prospecteur, vous pourrez le retrouver chez lui à Céladopole. Parlez-lui après avoir obtenu la CS02 : il vous apprendra à utiliser TUNNEL pour vous déplacer entre les villes, comme avec VOL. Contrairement à VOL, TUNNEL ne peut pas être utilisé pendant que vous surfez ou sur un quai au-dessus de l'eau.

![prospectors house](/screenshots/prospector's_house.png?raw=true) 

- Une zone secrète de Safrania se trouve près de la SYLPHE SARL. C'est par là que la TEAM ROCKET s'est infiltrée dans la ville sans se faire repérer ! Voilà donc comment ils sont arrivés là... Vous pourrez y améliorer votre SMOGOGO !

![saffron abandoned building](/screenshots/saffron_abandoned_building.png?raw=true)

- Il existe désormais 3 lieux où entraîner plus rapidement les Pokémon de faible niveau : à Carmin sur Mer, Céladopole et Safrania ! Le CLUB FITNESS DE CARMIN SUR MER, le CLUB DE COMBAT DE RUE et le DOJO KARATE. Chacun possède un niveau maximum : les Pokémon ayant dépassé ce niveau ne gagneront aucun point d'expérience. Les combats dans ces lieux rapportent trois fois plus d'expérience ! Idéal pour entraîner les nouveaux Pokémon que vous capturez si vous souhaitez changer votre équipe ! Vous pouvez désactiver ces nouvelles zones depuis les OPTIONS MONDE si vous le souhaitez.

![clubs 1](/screenshots/clubs1.png?raw=true)![clubs 2](/screenshots/clubs2.png?raw=true)![clubs 3](/screenshots/clubs3.png?raw=true)![clubs 4](/screenshots/clubs4.png?raw=true)

- Le MYSTIQUE DES CAPACITES, à Safrania, peut tout vous apprendre sur les nouvelles CAPACITES SIGNATURE de certains Pokémon. Elles leur permettent d'obtenir un bonus de puissance ou de précision sur certaines capacités.

![move mystic](/screenshots/move_mystic.png?raw=true)

- Vous pouvez désormais manger à bord de l'Océane pour soigner vos Pokémon pendant la traversée.

- Un donneur de capacités METRONOME a été ajouté sur la Route 12. Ce CROUPIER adore le chaos !

- Le vieil homme qui donnait la CT E-COQUE dans le jeu original vous apprendra désormais diverses capacités qui étaient autrefois des CT.

- Deux membres du DOJO KARATE se trouvent dans une maison à SAFRANIA. Ils veulent que vous battiez MORGANE pour venger leur défaite face à elle ! Si vous y parvenez, l'un d'eux apprendra à vos Pokémon des capacités supplémentaires qui étaient autrefois des CT dans le jeu original. L'autre apprendra à votre ALAKAZAM une attaque poing élémentaire de votre choix... MAIS UNE SEULE FOIS !

- Un escalier secret s'ouvre dans un bâtiment quelque part après être devenu Maître. Vous y trouverez le dernier échange de Pokémon du jeu ainsi que quelques découvertes intéressantes.

- Cette zone secrète vous permettra d'accéder à une zone encore plus secrète. Elle concerne MEWTWO. Vous devriez peut-être l'emmener avec vous. MEW aussi, pourquoi pas ! Ce que vous y découvrirez pourrait vous intéresser.

- Quelques objets ou panneaux ASTUCE ont été ajoutés dans des endroits jusque-là vides du monde.

- Plusieurs nouveaux objets cachés ont été ajoutés dans différentes zones du jeu.

- Vous pouvez ramasser plusieurs objets à la fois (exemple : vous avez trouvé 5 POTIONS).

- Faites un don au Centre Pokémon de la GROTTE pour découvrir le secret des Centres Pokémon : maintenez B avant de parler à l'infirmière pour bénéficier d'un service ultra-rapide !

- Quelqu'un vendra toutes les CT après que vous serez devenu Maître.

- Vous pourrez acheter des SUPER BONBONS après être devenu Maître, mais il vous faudra mener l'enquête pour découvrir comment.

- Les deux dresseurs supplémentaires de la Forêt de Jade présents dans Pokémon Jaune ont été ajoutés pour rendre la zone un peu moins vide.

## Contenu coupé restauré

- Si vous activez le mode musical OG+, le thème coupé de Giovanni sera joué lors de votre rencontre avec lui. Vous entendrez également une ancienne version de la musique de la Route 2 lors d'un échange de Pokémon dans le jeu.
- Le jeu contenait des textes inutilisés prévus pour vos défaites contre votre rival. Ils ont été réintégrés et fonctionnent désormais comme prévu !
- Une classe de dresseur inutilisée pour le Professeur Chen existait. Elle a été réintégrée au jeu. Retrouvez-le dans la Grotte Azurée après avoir vaincu le Conseil 4. Vous pouvez l'affronter autant de fois que vous le souhaitez : quittez simplement la zone et revenez.
- Plusieurs classes de dresseurs inspirées de sprites bêta ou inutilisés ont été réintroduites : RECRUE, RANGER, POMPIER, GAMIN COOL, SOLDAT, CHEF, BOXEUR, PRO FITNESS, SPRINTER. Vous les trouverez dans des lieux ou sur des routes auparavant vides !

![Rookie](/gfx/unused_prototype_sprites/rookie.png?raw=true) ![Ranger](/gfx/unused_prototype_sprites/ranger.png?raw=true) ![Firefighter](/gfx/unused_prototype_sprites/firefighter.png?raw=true) ![Cool Kid](/gfx/unused_prototype_sprites/cool_kid.png?raw=true) ![Soldier](/gfx/unused_prototype_sprites/soldier.png?raw=true) ![Chief](/gfx/unused_prototype_sprites/chief.png?raw=true) ![Fist Fighter](/gfx/unused_prototype_sprites/fist_fighter.png?raw=true) ![Chief](/gfx/unused_prototype_sprites/fitness_girl.png?raw=true) ![Chief](/gfx/unused_prototype_sprites/sprinter.png?raw=true)

- Des graphismes à l'apparence glacée, inutilisés dans le jeu et prévus pour les Îles Écume, ont été ajoutés à l'ensemble de décors de la Grotte. Ils sont désormais utilisés sur place !
![seafoam cut tiles](/screenshots/seafoam_islands_cut_content_tiles.png?raw=true)
- Certains dresseurs inutilisés appartenant à des classes existantes ont été ajoutés dans différents endroits auparavant vides.
- Le nouvel ensemble de décors de la CENTRALE ÉLECTRIQUE s'inspire de contenu coupé de Spaceworld 97.
- La maison de Nico et Julia sur la Route 19 s'inspire d'une maison visible dans les premières versions du jeu sur la Route 21.
- Le Volcan de Cramois'Île, en tant que zone, s'inspire d'une carte inutilisée nommée MOLTRES dans les premières versions du jeu.
- Vous pouvez activer ou désactiver la "Palette Arc-en-ciel", un contenu coupé de Céladopole, en parlant au panneau "Céladopole - La ville des rêves arc-en-ciel".
- Des éléments de décor inutilisés du DOJO DE COMBAT ont été réutilisés dans la nouvelle zone d'entraînement si l'option CLUBS est activée dans les OPTIONS MONDE.

## Changements visuels
- Le statut Brûlure possède désormais sa propre animation au lieu de réutiliser celle du poison.
- Les Poké Balls ont des animations légèrement différentes selon le type utilisé. Celle de la Master Ball est particulièrement réussie !
- Si vous jouez sur GBC/GBA et avez sélectionné SGB1, SGB2 ou GBC dans l'option COLOR du menu des options, les animations des capacités auront des couleurs adaptées (Flammèche sera rouge, Surf sera bleu, etc.).
- Avec les mêmes réglages de couleur (SGB1, SGB2 ou GBC), chaque type de Poké Ball aura une coloration différente.

![Pokeball Color](/screenshots/great_ball_color.png?raw=true)
- De nombreuses animations de capacités ont été améliorées.
- L'animation de VOL dans le monde extérieur a une fréquence d'images plus élevée et est beaucoup plus fluide.
- Une nouvelle animation a été ajoutée lorsque vous utilisez TUNNEL dans le monde extérieur.
- Le jeu prend désormais en charge des fondus plus fluides si vous activez FONDU GBC dans les options. Cette option fonctionne uniquement sur GBC.
- Avec les couleurs SGB1, la palette d'Argenta est légèrement plus grise que dans le jeu original.
- Avec les couleurs SGB1, SGB2 ou GBC, les Îles Écume ont une teinte bleu-violet au lieu d'avoir la même couleur que toutes les autres grottes du jeu.
- Avec les couleurs SGB1, SGB2 ou GBC, la Centrale Électrique a une teinte pâle au lieu d'utiliser le même mélange de vert et de bleu que toutes les routes avec de l'herbe.
- Avec les couleurs SGB1 ou SGB2, la salle d'Olga a une couleur proche de celle des Îles Écume (elle avait auparavant la même couleur que Bourg Palette).
- En mode couleur GBC, la palette des "Pokémon gris" a été rendue moins marron.
- Les sprites de dos de Spaceworld ont été retouchés pour les améliorer légèrement.
- Quelques sprites de face ont été très légèrement retouchés pour améliorer leur apparence.
- La palette de couleurs par défaut de certains Pokémon a été modifiée (par exemple, Voltorbe et Électrode sont rouges au lieu d'être jaunes comme dans le jeu original. Ne me demandez pas pourquoi ils étaient jaunes au départ).
- Vous pouvez désormais voir visuellement "le côté du bâtiment" depuis le toit du Centre Commercial de Céladopole et celui du Manoir de Céladopole.
- Les ascenseurs tremblent plus ou moins longtemps selon la distance jusqu'à l'étage sélectionné.
- Une petite animation se joue lorsque vous poussez un rocher sur un interrupteur sur la Route Victoire.
- Une petite animation se joue lorsque vous utilisez FLASH pour éclairer le Tunnel Rocheux.
- La Centrale Électrique utilise un nouvel ensemble de décors inspiré d'un décor bêta de Spaceworld 97, initialement prévu pour cette zone.
- Lorsque vous approchez d'un Pokémon immobile (ARTIKODIN/SULFURA/ELECTHOR/MEWTWO/RONFLEX), une animation spéciale se joue avant le début du combat.
- Si vous activez le mode OG+ Icons, vous verrez des Taupiqueurs sortir du sol et y replonger dans la Grotte Taupiqueur pour se cacher de vous.
- Si vous jouez sur SGB ou GBC, parler au panneau "Safrania - La ville des rêves arc-en-ciel" vous permettra de passer d'une palette Arc-en-ciel spéciale (code inutilisé du jeu original) à la palette d'origine.
- Une petite animation se joue désormais lorsque vous utilisez une Poupée dans un combat.
- Dans les Îles Écume, vous pouvez voir les courants marins se déplacer. Lorsque vous vous en approchez, des effets sonores de "courant rapide" se déclenchent également !

![Seafoam Currents](/screenshots/seafoam_currents.png?raw=true)

## Corrections de bugs
- Les dégâts de recul de PIED VOLTIGE / PIED SAUTE en cas d'échec infligent désormais davantage de dégâts (1/4 des dégâts qui auraient été infligés à l'adversaire).
- PUISSANCE augmente désormais correctement le taux de coups critiques (multiplié par 4 au lieu d'être divisé par 4).
- Les bonus de Badge ne sont plus appliqués plusieurs fois à chaque statistique lors de l'utilisation ou de la réception d'une capacité modifiant les statistiques.
- Les baisses de Vitesse et d'Attaque dues respectivement à la paralysie et à la brûlure ne sont plus appliquées plusieurs fois lors de l'utilisation ou de la réception d'une capacité modifiant les statistiques.
- Après avoir soigné une paralysie ou une brûlure avec un objet, les statistiques de Vitesse ou d'Attaque retrouvent correctement leurs valeurs initiales.
- Le cri de Nidorino est désormais correctement joué lors de l'introduction du Professeur Chen, au lieu de celui de Nidorina.
- Les capacités de soin comme SOIN n'échouent plus à tort lorsqu'elles restaurent exactement 255 PV.
- Les modifications des options du jeu depuis le menu principal (Continuer / Nouvelle partie / Options) sont désormais immédiatement enregistrées dans la sauvegarde en quittant le menu Options. (Auparavant, elles n'étaient enregistrées qu'après une sauvegarde effectuée en jeu.)
- Le bug permettant de contourner l'utilisation des Pierres évolutives a été supprimé : vous devez désormais utiliser une Pierre évolutive pour faire évoluer les Pokémon concernés.
- Gagner suffisamment d'expérience pour sauter un niveau ne fait plus manquer la capacité que le Pokémon aurait pu apprendre à ce niveau.
- L'apprentissage de capacités après une évolution fonctionne désormais correctement.
- Evoli apprend désormais toujours une capacité propre à son type lors de son évolution, quel que soit son niveau au moment de celle-ci.
- Les bonus de statistiques de MUR LUMIERE et de PROTECTION sont plafonnés à 999 afin d'éviter les dépassements de capacité.
- Major Bob indique que le Badge Foudre augmente la Vitesse, mais le code augmentait en réalité la Défense. Il augmente désormais bien la Vitesse, comme indiqué dans le texte.
- Koga indique que le Badge Âme augmente la Défense, mais le code augmentait en réalité la Vitesse. Il augmente désormais bien la Défense, comme indiqué dans le texte.
- Lorsqu'un Pokémon apprenait une nouvelle capacité en combat, le bruitage « Pouf ! » ne fonctionnait pas correctement et était remplacé par un son aléatoire. Il fonctionne désormais correctement.
- Lorsque vous êtes transformé en un autre Pokémon grâce à MORPHING, vous ne pouvez plus permuter l'emplacement de vos capacités. Cela provoquait des bugs pouvant entraîner un plantage du jeu.
- Les personnages non-joueurs respectent désormais correctement leurs orientations programmées (face, gauche, etc.).
- L'animation de DAMOCLES lorsqu'elle est utilisée par l'adversaire a été corrigée.
- Perdre tous ses Pokémon dans le Parc Safari ne provoque plus de bug du jeu.
- Tenter de remplacer le Pokémon actuellement au combat ou un Pokémon K.O. ne provoque plus un petit bug visuel.
- Un petit bug de détection des collisions dans la Caverne Azurée a été corrigé.
- Les ralentissements causés par le remplacement des blocs de décor lors du chargement d'une carte ont été considérablement réduits.
- Les effets sonores joués pendant les dialogues fonctionnent désormais correctement lorsque l'option de texte instantané est activée.
- Les blocs de décor ne présentent plus occasionnellement de changement visuel lors du chargement d'une carte.
- Utiliser CLONAGE avec exactement le nombre de PV nécessaire ne met plus votre Pokémon K.O. Il lui reste désormais 1 PV.
- L'écran ne clignote plus en blanc pendant une image lors de l'entrée dans un combat ou un bâtiment sur Game Boy originale ou Game Boy Color.
- La POKéFLUTE détecte désormais correctement les Pokémon sauvages endormis lorsqu'elle est utilisée en combat.
- Sur Game Boy originale, les portraits des Dresseurs qui défilent au début du combat apparaissent désormais sous forme de silhouettes, comme sur Super Game Boy et Game Boy Color.
- Le panneau de la Route 17 peut désormais être lu depuis le dessous.
- Il n'est plus possible de se retrouver bloqué par le cambrioleur au 3e étage du Manoir Pokémon.
- Si tous vos Pokémon sont K.O. à l'exception de celui actuellement au combat, le mode CHOIX ne vous demande plus si vous souhaitez changer de Pokémon avant que l'adversaire en envoie un autre.
- Le LOKHLASS du zoo de Parmanie peut désormais nager dans son bassin, comme cela était prévu dans le code.
- Les capacités empêchant la fuite n'infligent plus de dégâts continus par erreur aux Pokémon qui y sont immunisés. Exemple : LIGOTAGE contre un Pokémon Spectre.
- Dans le jeu original, si vous ou votre adversaire vous blessiez dans votre confusion ou étiez totalement paralysé pendant l'utilisation de TUNNEL ou VOL, le Pokémon pouvait rester dans un état invulnérable, rendant toutes les attaques inefficaces. Ce bug a été corrigé dans les combats Link et ne se produit plus sur les Pokémon adverses en jeu normal. Cependant, puisqu'il s'agit d'un bug amusant, il peut toujours se produire sur le joueur : vous deviendrez alors invulnérable.
- Dans le jeu original, si votre adversaire utilisait LILLIPUT ou CLONAGE, que vous ouvriez le menu COMBAT, le quittiez, ouvriez le menu équipe Pokémon, consultiez l'écran de statut d'un Pokémon puis reveniez au combat, le sprite adverse était complètement déformé. Ce bug a été corrigé.
- Effectuer la même manipulation que ci-dessus contre un SPECTRE non identifié révélait son identité. Ce n'est désormais plus le cas.
- Après avoir sauvegardé dans le Tunnel, passer de l'écran-titre à l'écran Continuer, puis revenir à l'écran-titre et retourner à l'écran Continuer assombrissait ses couleurs. Elles restent désormais normales.
- Les capacités drainant des PV échouent désormais contre les Pokémon protégés par CLONAGE, comme cela était initialement prévu dans le code.
- Utiliser COPIE après un changement de Pokémon adverse ne copie plus systématiquement la capacité dans le deuxième emplacement, quel que soit votre choix.
- Utiliser COPIE après un changement de Pokémon adverse ne perturbe plus temporairement l'interface du combat.

## Changements
- Les Dresseurs ont généralement des équipes un peu moins spécialisées dans un type et des Pokémon plus variés.
- Les équipes des Champions d'Arène restent spécialisées dans un type, mais peuvent comporter un ou deux Pokémon nouveaux ou différents.
- Votre rival utilise différentes équipes tout au long du jeu, mais conserve son Pokémon de départ.
- Une pierre de chaque type élémentaire est cachée avant le Tunnel.
- La Potion soigne 50 PV.
- La Super Potion soigne 100 PV.
- Les CS n'empêchent plus un Pokémon d'être placé à la Pension.
- Safrania se trouve après Céladopole dans l'ordre des destinations de Vol, au lieu de se trouver après le Plateau Indigo pour une raison quelconque.
- Le mécanisme de l'Arène de Carmin sur Mer ne se réinitialise plus si vous choisissez le mauvais deuxième interrupteur. Fini de perdre du temps à cause du hasard !
- Le drapeau « Téléportation » est désormais activé lorsque vous utilisez Vol vers une ville ou que vous entrez dans un Centre Pokémon.
- L'arbre à couper sur la Route 9 a été légèrement déplacé vers la droite afin que le code permettant de dégager l'arbre s'exécute instantanément lors de votre arrivée sur cette route, plutôt que pendant que vous regardez l'arbre à couper.
- La corniche située sous la Pension a été abaissée d'une case afin d'éviter de sauter accidentellement dans le vide.
- La CANNE permet désormais de pêcher des Poissirène en plus des Magicarpe.
- La SUPER CANNE permet de pêcher de nombreux Pokémon aquatiques. Les Pokémon obtenus dépendent de l'endroit où vous pêchez : en mer ou dans un étang ou un lac.
- La MEGA CANNE permet de pêcher des Pokémon de niveau supérieur ou, si cette fonctionnalité est activée, constitue le seul moyen de capturer certains Pokémon aquatiques aux palettes de couleurs alternatives dans des lieux précis ! Il est temps de partir à la recherche d'un Poissirène bleu !
- Les vitamines comme le PV PLUS sont environ trois fois plus efficaces.
- Le PP PLUS augmente au maximum les PP d'une capacité en une seule utilisation.
- Ronflex, Ramoloss et Flagadoss se déplacent lentement dans le menu de l'équipe, quel que soit leur nombre de PV.
- Peter se tournera désormais vers vous lorsque vous serez sur le point de l'affronter, et vous vous tournerez également vers lui.
- Les cases de rives d'eau déclenchent désormais des rencontres avec des Pokémon aquatiques, SAUF sur la Route 20, afin de préserver la méthode originale de rencontre avec MissingNo.
- La case d'herbe en forme d'étoile dans la Forêt de Jade et le Parc Safari déclenche désormais correctement des rencontres avec des Pokémon.
- Chaque Badge augmente désormais de 10 niveaux le niveau des Pokémon échangés qui vous obéissent, jusqu'au Badge Âme, au lieu d'une augmentation de 20 niveaux tous les deux Badges. Le texte explicatif des Badges reste toutefois inchangé. Cette modification vise simplement à faciliter l'utilisation des Pokémon obtenus par échange dans le jeu au cours d'une partie normale.
- Un texte inutilisé concernant Porygon a été ajouté à l'écran d'ordinateur du 11e étage de la Sylphe SARL.
- De nouveaux textes ont été ajoutés à des objets qui n'avaient auparavant aucun texte ou qui réutilisaient parfois des textes génériques. (Exemple : certaines poubelles dans les maisons des habitants possèdent désormais un texte qui leur est propre.)
- Vous pouvez désormais utiliser un plus grand choix de caractères dans les surnoms des Pokémon et du joueur.
- Dans le jeu original, si vous ouvriez le menu OPTIONS dans une GROTTE alors qu'il faisait sombre, le menu était également sombre. Il affiche désormais ses couleurs normales.
- Les infirmières des Centres Pokémon vous reconnaîtront désormais après votre victoire à la Ligue et vous traiteront un peu différemment. Vous êtes célèbre !
- Le texte de certains Dresseurs qui disaient des choses incohérentes après votre victoire contre le Champion de l'Arène dans laquelle ils se trouvent a été modifié pour tenir compte de votre victoire (3 dans l'Arène de Carmin sur Mer, 1 dans l'Arène de Céladopole et 1 dans l'Arène de Parmanie).
- M.Psy exige désormais que vous battiez le DOJO KARATE avant de vous donner la CT PSYKO.
- Les Dresseurs qui proposent des échanges dans le jeu possèdent désormais chacun un DO unique au lieu d'avoir simplement le nom DRESSEUR.
- Le gardien du PARC SAFARI vous adressera des paroles différentes si vous avez déjà obtenu la CS03, au lieu de vous demander de la récupérer alors que vous la possédez déjà.
- La SAFARI BALL possède désormais un coefficient de capture de 1, ce qui la rend plus efficace pour capturer des Pokémon ayant tous leurs PV.
- Lorsque vous vous dirigez vers la sortie, votre rival dans la Sylphe SARL effectue désormais une "téléportation" visuelle lorsqu'il atteint la case de téléportation, au lieu de simplement disparaître.

## Modifications des capacités
- ENTRAVE empêche l'adversaire d'utiliser la capacité qu'il avait précédemment sélectionnée. S'il n'a pas encore choisi de capacité, une capacité aléatoire est sélectionnée à la place. Précision : 85 %. Dure de 2 à 7 tours.
- Les capacités d'immobilisation ne durent plus que 2 ou 3 tours, mais infligent davantage de dégâts pour compenser. 2 chances sur 3 de durer 2 tours, et 1 chance sur 3 de durer 3 tours.
- 7 capacités rarement utilisées ont été renommées et modifiées afin de leur attribuer des effets bien plus utiles (principalement inspirés de capacités prototypes inutilisées) :
  - CONSTRICTION est désormais VAMPI-STATIK : puissance de base de 75, type Électrik, soigne les altérations de statut du lanceur ou d'un Pokémon de l'équipe si le lanceur n'en subit aucune. Précision : 100 %. (Inspirée des capacités prototypes inutilisées `PARALYZING SCISSORS` et `ELEKITER`.)
  - BELIER est désormais COUP D'CHAUD : puissance de base de 75, type Feu, 30 % de chances de brûler l'adversaire, précision de 100 %. Si elle est utilisée par un Pokémon de type Feu, elle a également 40 % de chances d'augmenter sa statistique SPECIAL d'un niveau. (Inspirée de la capacité prototype inutilisée `MEGA FIRE`.)
  - TELEKINESIE est désormais MUR DE FEU : puissance de base de 20, type Feu, brûle l'adversaire, précision de 90 %. (Inspirée de la capacité prototype inutilisée `F WALL`.) Si elle est utilisée sur un Pokémon déjà brûlé, sa puissance passe à 40. Si elle est utilisée à nouveau après cela, sa puissance augmente jusqu'à un maximum de 80. Si le lanceur est au moins au niveau 50, les puissances passent respectivement à 80 et 140.
  - RIPOSTE est désormais VAMPI-POING : puissance de base de 75, type Combat, absorbe des PV, précision de 100 %.
  - COUPE-VENT est désormais ATTERRISSAGE : restaure la moitié des PV max.
  - SOUPLESSE est désormais FRAP'TOXIK : puissance de base de 80, type Poison, aucun effet supplémentaire, précision de 100 %. Sa puissance passe à 130 si la cible est empoisonnée. (Inspirée de la capacité prototype inutilisée `GASTRO ACID`.)
  - COMBO-GRIFFE est désormais GRIFFE-SABLE : puissance de base de 40, type Sol, aucun effet supplémentaire, précision de 100 %. (Une capacité de type Sol disponible dès le début du jeu.) (Inspirée des nombreuses capacités physiques supprimées du jeu.)
- Certaines capacités relativement inutiles ont été rendues un peu moins inutiles :
  - CYCLONE : puissance de base de 110, type Vol, 30 % de chances de rendre confus, précision de 85 %.
  - REPLI : restaure environ un tiers des PV max et augmente la DÉFENSE. N'a aucun effet si les PV sont au maximum.
  - CROISSANCE : restaure environ un tiers des PV max et augmente le SPÉCIAL. N'a aucun effet si les PV sont au maximum.
  - BOUL'ARMURE : fait en sorte que toutes les capacités SUPER EFFICACES infligent des dégâts normaux au lanceur jusqu'à ce qu'il soit remplacé.
  - YOGA : augmente l'ATTAQUE, la VITESSE et le SPÉCIAL d'un niveau.
  - SACRIFICE : puissance de base de 60, type Combat, augmente l'ATTAQUE d'un niveau, précision de 100 %.
  - COUPE : puissance de base de 70, type Insecte, aucun effet supplémentaire, précision de 100 %.
  - FLASH : puissance de base de 60, type Électrik, capacité prioritaire, 10 % de chances d'apeurer l'adversaire, précision de 100 %.
  - ADAPTATION : permet au lanceur d'alterner entre le mode DÉFENSE et le mode ATTAQUE. En mode DÉFENSE, tous les dégâts subis sont divisés par deux. Le mode ATTAQUE annule le mode DÉFENSE et déclenche une attaque garantie SUPER EFFICACE contre l'adversaire.
  - POING COMETE : puissance de base de 60, type Combat, capacité prioritaire, précision de 100 %.
  - POING-KARATE, POING COMETE, ULTIMAPOING, FORCE et ULTIMAWASHI sont désormais toutes des capacités de type Combat.
  - FORCE POIGNE : puissance de base de 75, type Insecte, 30 % de chances de paralyser l'adversaire, précision de 100 %.
  - CRU-AILE : puissance de base de 50, type Vol, capacité prioritaire, précision de 100 %.
  - PATIENCE : augmente l'ATTAQUE et la DÉFENSE d'un niveau.
  - EXPLOSION : puissance de base de 140, type Feu, inflige de lourds dégâts de recul, précision de 100 %. Si le lanceur possède moins d'un tiers de ses PV, sa puissance passe à 250 et la DÉFENSE de l'adversaire est divisée par deux, mais le lanceur tombe immédiatement K.O.
  - DESTRUCTION : puissance de base de 140, type Roche, inflige de lourds dégâts de recul, précision de 100 %. Si le lanceur possède moins d'un tiers de ses PV, sa puissance passe à 250 et la DÉFENSE de l'adversaire est divisée par deux, mais le lanceur tombe immédiatement K.O.
  - COUP D'BOULE : puissance de base de 100, type Roche. Si elle échoue, le lanceur subit des dégâts de chute, comme avec PIED SAUTÉ et DOUBLE PIED. Précision : 90 %.
  - PICPIC : puissance de base de 42, type Roche, touche 2 ou 3 fois (50 % de chances pour chaque résultat), précision de 100 %.
  - GAZ TOXIK : puissance de base de 60, type Poison, taux de coups critiques élevé, 10 % de chances d'empoisonner l'adversaire, précision de 100 %.
  - VOL-VIE : puissance de base de 70, type Insecte, absorbe des PV, précision de 100 %.
  - EBOULEMENT et JET-PIERRES ont désormais une précision de 100 %.
  - MIMIQUE : devient une capacité prioritaire et reproduit toujours la dernière attaque utilisée par l'adversaire, même si le Pokémon qui l'a lancée est tombé K.O. entre-temps.
  - COPIE : tu peux toujours choisir précisément la capacité à imiter, mais elle est désormais utilisée dès le tour où tu la copies.
  - OSMERANG : puissance de base de 60, touche deux fois, précision de 95 %, 30 % de chances de réduire la VITESSE de l'adversaire. Peut également toucher les Pokémon de type Vol avec des dégâts neutres, contrairement aux autres capacités de type Sol.
  - CROC FATAL : inflige désormais des dégâts équivalents aux deux tiers des PV de l'adversaire au lieu de la moitié. Très pratique pour capturer des Pokémon rares !
  - TELEPORT : devient enfin utile lors des combats contre des Dresseurs ! Le lanceur est remplacé et récupère 25 % de ses PV au passage. Fonctionne toujours comme auparavant lorsqu'elle est utilisée par un Pokémon sauvage.
  - TORGNOLES : inflige deux fois plus de dégâts aux Pokémon endormis ! Mais les réveille également.
  - SONICBOOM : capacité prioritaire, type Spectre, puissance de 50. Si elle est utilisée dès le premier tour où le lanceur peut attaquer, elle apeure systématiquement l'adversaire.
  - ACIDARMURE : combine les effets de MUR LUMIÈRE et de REFLET en une seule capacité.
  - ACIDE : réduit toujours l'ATTAQUE ou la DÉFENSE de l'adversaire d'un niveau.
  - VAMPIGRAINE : inflige davantage de dégâts à chaque tour selon la résistance de l'adversaire au type Plante. Les dégâts restent fixés à 1/16 de ses PV par tour s'il résiste au type Plante, passent à 1/8 si le type Plante lui inflige des dégâts normaux, et à 3/16 s'il y est faible.
  - LILLIPUT n'affecte pas les Pokémon de type Feu. (Permet de mieux contrer cette capacité.)
  - JET DE SABLE n'affecte pas les Pokémon de type Sol ou Vol. (Permet de mieux contrer cette capacité.)
  - TOXIK : précision de 100 % lorsqu'elle est utilisée par un Pokémon de type Poison.
  - GRINCEMENT : réduit toujours la DÉFENSE de deux niveaux, mais ne rate désormais jamais sa cible. Provoque également un effet appelé "Cris résonnants" qui réveille tous les Pokémon endormis et empêche l'utilisation de capacités provoquant le sommeil. Cet effet dure pendant tout le combat ! La capacité est automatiquement utilisée lorsqu'un Pokémon qui la connaît est visé par une capacité censée l'endormir. Dites NON aux capacités de sommeil si vous le souhaitez !
- Certains Pokémon disposent désormais de CAPACITÉS SIGNATURE ! Cela signifie qu'ils infligent davantage de dégâts ou bénéficient d'une meilleure précision avec certaines capacités spécifiques. Par exemple, si ABO utilise ACIDE, sa puissance sera de 100 au lieu de 50. Un PNJ à Safrania peut vous indiquer quels Pokémon possèdent des capacités signature et quels bonus elles procurent. Vous pouvez désactiver cette fonctionnalité en désactivant l'option MYSTIQUE DES CAPACITÉS dans les OPTIONS MONDE.
- De nombreuses autres modifications ont été apportées aux capacités. Consultez votre CAPADEX en jeu pour découvrir les effets d'une capacité que vous venez de rencontrer, ou consultez le wiki pour accéder à la liste complète des capacités. N'hésitez pas à essayer presque toutes les capacités au lieu de les écarter d'emblée. À l'exception de TREMPETTE, qui ne sert toujours à rien, comme d'habitude.

## Modifications des types des Pokémon
Ces changements visent à rendre certains Pokémon plus amusants à jouer / plus uniques / moins mauvais.
Dès l'obtention de votre premier Badge (Badge Roche) à Argenta, un PNJ dans une maison de la Route 23 du Plateau Indigo, après le premier garde, vous permettra de choisir entre les nouveaux types et les types d'origine de chaque Pokémon. Je recommande toutefois d'en conserver au moins quelques-uns, car ils sont amusants et l'équilibrage du jeu et des capacités en tient compte.
- Feunard : Feu/Spectre
- Akwakwak : Eau/Psy
- Hypocéan : Eau/Dragon
- Ossatueur : Sol/Spectre
- Kabuto/Kabutops : Roche/Insecte
- Papilusion : Insecte/Psy
- Doduo/Dodrio : Vol/Sol
- Voltorbe/Électrode : Electrik/Feu
- Rapasdepic : Vol/Combat
- Krabboss : Eau/Sol
- Scarabrute : Insecte/Combat
- Élektek : Electrik/Combat
- M. Mime : Psy/Spectre
- Sabelette/Sablaireau : Sol/Normal (dégâts de Tranche augmentés !)
- Ponyta/Galopa : Feu/Normal
- Poissirène/Poissoroy : Eau/Normal
- Empiflor : Plante/Dragon

De plus, le type SPECTRE devient un "type dynamique". Il inflige des dégâts physiques ou spéciaux selon les statistiques de base du Pokémon :

- Si son SPÉCIAL de base est supérieur à son ATTAQUE, les capacités Spectre utilisent le SPÉCIAL.
- Sinon, elles utilisent l'ATTAQUE du lanceur et la DÉFENSE de la cible.

Cela rend notamment Ectoplasma plus utile, tout en permettant aux Pokémon physiques de profiter de leurs statistiques avec les capacités Spectre.

## Modifications de l'IA des Dresseurs
- Les PP des adversaires peuvent être suivis si l'option PP des PNJ est activée dans les options du jeu.
- L'IA n'utilisera plus Réflexion ou Amnésie en boucle simplement parce que votre Pokémon est faible face aux capacités Psy. La routine de sélection des capacités super efficaces ignore désormais celles qui n'infligent aucun dégât.
- De même, l'IA évitera d'utiliser des capacités mettant K.O. en un coup si elles ne peuvent pas fonctionner, même si elles semblent super efficaces. Elle les utilisera toutefois si elles ont une chance de réussir.
- L'utilisation d'objets et les changements de Pokémon par l'IA auront toujours lieu au début du tour, comme pour le joueur, et non au moment où le Dresseur doit jouer.
- La plupart des Dresseurs éviteront d'utiliser Dévorêve si votre Pokémon n'est pas endormi.
- La plupart des Dresseurs éviteront d'utiliser Vampigraine, Entrave, Mur Lumière, Protection, Puissance, Brume et autres capacités à effet persistant si leur effet est déjà actif et qu'une nouvelle utilisation serait inutile.
- La plupart des Dresseurs éviteront les capacités provoquant la confusion si votre Pokémon est déjà confus.
- La plupart des Dresseurs éviteront les capacités de soin comme Soin lorsque leurs Pokémon ont tous leurs PV.
- La plupart des Dresseurs éviteront les capacités prioritaires si votre Pokémon est invulnérable grâce à Vol ou Tunnel.
- Les Dresseurs plus expérimentés privilégieront les capacités prioritaires si votre Pokémon est plus rapide que le leur.
- Les Dresseurs plus expérimentés privilégieront les capacités qui absorbent des PV, comme Méga-Sangsue, lorsque leurs Pokémon ont peu de PV.
- Les Dresseurs plus expérimentés utiliseront Copie si elle permet d'obtenir une capacité super efficace.
- Les Dresseurs plus expérimentés privilégieront encore davantage les capacités infligeant des dégâts quadruplement super efficaces.
- Les Dresseurs experts privilégieront les capacités de soin comme Soin lorsque leurs Pokémon ont peu de PV.
- Les Dresseurs experts privilégieront fortement Dévorêve si votre Pokémon est endormi.
- Les Dresseurs experts tenteront d'infliger des altérations de statut à vos Pokémon s'ils n'en ont aucune.
- Les Dresseurs disposant d'objets augmentant les statistiques, comme Attaque +, ne les utiliseront que s'ils estiment pouvoir le faire sans risque.

## Modifications Audio
- Si vous sélectionnez le mode audio OG+ dans les options, un nouveau morceau de 2 minutes, composé par l'auteur et inspiré du court thème d'évolution original, sera joué dans le Parc Safari.
- À la 5e page des options, vous pouvez activer une option permettant de mettre la musique de l'overworld en pause pendant les combats, puis de la reprendre à la fin, au lieu de la relancer depuis le début après chaque rencontre ou combat.
- Les fantômes de la Tour Pokémon disposent désormais d'un effet sonore lorsqu'ils apparaissent.
- Un petit effet sonore est joué lors de l'utilisation d'une CT ou d'une CS.
- Pousser un rocher dans un trou sur les Îles Écume ou la Route Victoire déclenche désormais un effet sonore et un retour visuel.
- Tomber dans un trou sur les Îles Écume ou la Route Victoire déclenche désormais un effet sonore.
- Le thème de Giovanni (musique inutilisée de Pokémon Jaune) est joué lors de sa rencontre. Nécessite le mode MUSIQUE OG+.
- Le thème de victoire bêta (thème de victoire des combats "Guide") est joué après avoir vaincu une Dresseuse. Nécessite le mode MUSIQUE OG+.
- Le thème de soin bêta (thème de soin "Bourg Palette") est joué lorsque vous vous reposez chez vous à BOURG PALETTE. Nécessite le mode MUSIQUE OG+.
- Le Conseil des 4 utilise désormais entièrement le thème des combats d'Arène, au lieu d'utiliser le thème de combat classique pour ses trois premiers membres.
- Un petit effet sonore est désormais joué lorsque vous jetez un objet.
- Un petit effet sonore est joué lorsque vous montez sur votre vélo ou en descendez, mais uniquement si l'option SON VELO est désactivée.
- Un petit effet sonore est joué lorsque vous poussez un rocher sur un interrupteur dans la Route Victoire.
- Un petit effet sonore est joué lorsque vous éclairez la Grotte Sombre avec FLASH.
- Un petit effet sonore est joué lorsque les portes derrière les trois premiers membres du Conseil des 4 s'ouvrent après leur défaite.
- En mode MUSIQUE OG+, les cris de 6 Pokémon (Têtarte, Rafflesia, Poissirène, Rhinocorne, Amonita et Métamorph) sont légèrement modifiés afin qu'ils ne soient plus des copies exactes des cris d'autres Pokémon.
- Le volume de la musique diminue lorsque vous accédez à l'écran de surnom des Pokémon.
- Un effet sonore inutilisé du jeu est réemployé lors de quelques nouveaux événements, notamment dans la zone VOLCAN.
- Un effet sonore est joué lorsque Léo entre dans le téléporteur.
- Un effet sonore est joué lorsque vous utilisez un PP Plus pour augmenter les PP max d'une capacité.

## Visuels de Pokémon Midori (Version Verte)
Les éléments visuels propres à la version japonaise Pokémon Midori (version Verte) ont été intégrés dans VertPur.
- Machines à sous

![Green Slots](/screenshots/green_slots.png?raw=true)
- Bordures SGB

![Green SGB Border](/screenshots/green_title_sgb_border.png?raw=true)
- Écran Titre

## Ce qui restera inchangé
- Je ne modifierai pas les couleurs, tilesets, musiques, sprites, etc. pour leur donner le style de la génération 2.
- Je n'implémenterai pas la séparation physique/spécial. L'équilibrage du jeu repose sur son absence.
- Je ne séparerai pas la statistique SPECIAL en DEFENSE SPECIAL et ATTAQUE SPECIAL. L'équilibrage repose sur la statistique spéciale combinée.
- Je n'ajouterai pas les types Ténèbres, Acier ou Fée.
- Je ne modifierai pas le tableau des types en dehors des options déjà proposées.
- Je ne proposerai pas de version sans les changements des statistiques de base.
- Je ne proposerai pas de version sans les changements des attaques.
- Je ne proposerai pas de version sans les changements des capacités apprises, des CT et des équipes des dresseurs.
- Je n'ajouterai pas les Pokémon bêta au jeu (presque tous les Pokémon bêta intéressants de la génération 1 ont déjà été réutilisés comme Pokémon officiels dans les jeux suivants).
- Je n'ajouterai pas de "MULTI EXP" au jeu. L'équilibrage repose sur le fait d'entraîner chaque Pokémon de son équipe, et c'est une caractéristique de la génération 1 ! Il faut de la discipline pour tous les entraîner au lieu d'en délaisser certains. Plus tard dans le jeu, plusieurs moyens permettent de faire monter rapidement ses Pokémon : duplication de Super Bonbons grâce au glitch de duplication d'objets, achat de Super Bonbons dans une zone secrète, PUCE EXP, entraînement facile et répétable dans la ZONE SAFARI et Pokémon sauvages donnant davantage d'EXP sur la Route 23. Donc pas d'inquiétude.
- Je n'ajouterai pas d'indicateur "Pokémon capturé" pendant les combats. Pourquoi ? Cela change les sensations de jeu. Avec cette fonctionnalité, on n'a pratiquement plus besoin de consulter le Pokédex. Je pense aussi que l'absence de cet indicateur fait partie de l'identité de la génération 1 : il faut se souvenir des Pokémon déjà capturés.
- Je n'ajouterai pas de "Maître des capacités". Cela change beaucoup l'expérience de la génération 1, où il faut bien réfléchir avant d'oublier une capacité apprise. Pas d'inquiétude : la plupart des bonnes capacités peuvent être réapprises grâce aux CT. Les meilleures capacités arrivent plus tard dans les listes d'apprentissage, il est donc peu probable que vous les manquiez.
- Si vous préférez moins de changements tout en conservant les améliorations de confort et les corrections de bugs, je vous recommande de jeter un œil au ROM hack shinpokered.
