
import sys
import os

import math

from colorama import init
from termcolor import colored

from playsound import playsound
import easygui 

import matplotlib.pyplot as plt
from matplotlib.widgets import Button







def menu():
    
    
    chosen_element = 0;
    
    print("\n!")
    print(colored("##::::'##:'########:::::::'##:::::'#######::::'#####::::'#######:::'#######::","cyan"))
    print(colored("###::'###: ##.....:::::::: ##::::'##.... ##::'##.. ##::'##.... ##:'##.... ##:","blue"))
    print(colored("####'####: ##::::::::::::: ##::::..::::: ##:'##:::: ##:..::::: ##:..::::: ##:","cyan"))
    print(colored("## ### ##: ######::::::::: ##:::::'#######:: ##:::: ##::'#######:::'#######::","blue"))
    print(colored("##. #: ##: ##...::::'##::: ##::::'##:::::::: ##:::: ##:'##::::::::'##::::::::","cyan"))
    print(colored("##:.:: ##: ##::::::: ##::: ##:::: ##::::::::. ##:: ##:: ##:::::::: ##::::::::","blue"))
    print(colored("##:::: ##: ########:. ######::::: #########::. #####::: #########: #########:","cyan"))
    print(colored("..:::::..::........:::......::::::.........::::.....::::.........::.........::","blue"))

    

    print (colored("#############################################################################","red"))
    print ("########                                                             ########")
    print ("########                       MAXIPILE HELPER                       ########")
    print ("######## ----------------------------------------------------------- ########")
    print ("########                 Lycée Alfred Mézières Longwy                ########")
    print ("######## ----------------------------------------------------------- ########")
    print ("########                                                             ########")
    print ("########                    Choisissez une option:                   ########")
    print ("########                                                             ########")
    print ("########        1) nb de possibilité |  2) Vérificateur de pile      ########")
    print ("########        3) Exit              |     et mot de Dyck            ########")
    print ("########                                                             ########")
    print ("########                                                      v 1.6  ########")
    print (colored("#############################################################################","red"))
    chosen_element = input("Entrez un nombre entre 1 et 3: ")
    
    if int(chosen_element) == 2:
        ###début du script 2 VERIFICATEUR DE PILE###
            print("\n")
            print(colored(" ___                                                                 ___   ","magenta"))
            print(colored("|   |                                                               |   |  ","green"))
            print(colored("|   | ___                                                       ___ |   |  ","magenta"))
            print(colored("|   ||   |                   BOOK STACK SOLVER                 |   ||   |  ","green"))
            print(colored("|   ||   | ___                                             ___ |   ||   |  ","magenta"))
            print(colored("|   ||   ||   |                                           |   ||   ||   |  ","green"))
            print(colored("|   ||   ||   |                                           |   ||   ||   |  ","magenta"))
            print(colored("|   ||   ||   |            ====================== >       |   ||   ||   |  ","green"))     
            print(colored("| 3 || 2 || 1 |                                           | 1 || 2 || 3 |  ","magenta"))
            print(colored("|___||___||___|               by Dr Septimus              |___||___||___|  ","green"))
            print("\n")
            input("Appuyez sur une touche pour lancer le programme ")
            print(colored("@@@ BOOK STACK SOLVER @@@ by Dr Septimus","red"))
            print("\n")

            abs_ord = []                                                                                                                      # pile servant à contenir les dimensions du graphique en fonction du nombre de livre
            liste_livre=[]                                                                                                                    # pile initiale de livre à trier
            liste_pilemilieu=[]                                                                                                               # pile intermédaire (pile du milieu) de livre 
            mot_de_Dyck = []                                                                                                                  # liste qui contiendra le mot de Dyck en lettre (A et B) 
            mot_de_Dyck_int = []                                                                                                              # liste qui contiendra le mot de Dyck en valeur numérique (0 et 1) (plus facile pour leur traitement dasn la suite du programme)


            ##### interaction avec utilisateur #####
            n = int(input("Veuillez entrer le nombre de livre (plus grand que 1) : "))
            print("\n")
            liste_pilefin=[0]                                                                                                                 # pile finale de livre, pour effectuer la première comparaison, un élement doit se trouver dasn la liste pile fin et puisque le premier élement qui doit arriver dans la pile fin si le pile initiale est triable est 1, la valeur pour la comparaison est 0

            ##### Création du graphique #####

            for i in range (0,n+1):                                                                                                           # puisque le graphique est un carré abs = ord, pour 3 livres, carré de 3x3 ...
                abs_ord.append(i)                                                                                                              


            plt.figure('Maxipile Helper Dyck représentation v1.0')                                                                            # nomme la fenêtre du programme
            plt.plot (abs_ord, abs_ord,'black',linestyle='--')                                                                                # créé un graphique "carré" de x par y=x et trace la diagonale 
            plt.locator_params(axis= "both", integer=True, tight=True)                                                                        # Permet d'avoir suelement des entiers sur les deux axes
            plt.margins(0)                                                                                                                    # Par défaut, matplotlib ajoute 5% d'espace dans les coins du graphique, peremet de gérer cet espace ne % 
            plt.grid(True)                                                                                                                    # active le quadrillage 
            plt.gca().set_aspect("equal")                                                                                                     # conserve des proprtions unitaires égales pour les deux axes
            plt.xlabel("A",color='b',fontweight='bold' ,fontsize= 14)                                                                         # titre axe des abscisse
            plt.ylabel("B",color='b',fontweight='bold',rotation=0, fontsize= 14)                                                              # titre axe des ordonnées 
            plt.suptitle('Représentation graphqiue du mot de Dyck :', fontsize=14, fontweight='bold')                                         # titre du graphqiue

            # Bouton d'aide '?'

            def helptxt(help):                                                                                                                # création de la fonction help qui renvois un message d'aide
                help_text = easygui.msgbox("Les mots de Dyck sont composées de la manière suivante :\n\n- Lorsque l'on déplace\
 un livre de la pile initiale vers la pile du milieu, on ajoute à la suite du mot, la lettre (A) qui correspond\
 à un déplacement d'une unité sur l'axe horizontale.\n\n- Lorsque l'on déplace un livre de la pile du milieu\
 vers la pile finale, on ajoute à la suite du mot, la lettre (B) qui correspond à un déplacement\
 d'une unité sur l'axe verticale.\n\nUne pile est triable lorsque les deux sommets opposés, liés par \
la diagonale, sont reliés par les segments rouges.", title="Maxipile Helper Dyck représentation v1.0 - aide")

 

            ##### Interaction utilisateur 2 #####

            for i in range (0,n):                                                                                                             # i position des livres de 0 a n ( n valeur entrée par l'utilisateur)
                print("Veuillez associer aux positions suivantes le numéro du livre correspondant en commançant avec 0 le livre le plus à gauche de la pile : position",colored(i,"green" ))
                item = int(input())                                                                                                           # l'utilisateur entre les livres correpsondant aux position indiquées
                liste_livre.append(item)                                                                                                      # le numéro du livre corespondant à la position est ajouté à la liste_livre dans l'ordre de la saisie  
            print("\n")
            print("Votre pile est", colored(liste_livre, "yellow"))

            liste_livre.reverse()                                                                                                             # inversion de l'ordre des éléments dans la pile liste_livre, car plus facile de travailler avec un index [0] (le livre indexé [0] étant celui qui partira vers la pile _milieu)                                                 
            


            testsomme = int(((n**2+n)/2))                                                                                                     # Correspond à la somme des numéros des livres attendu dans liste_livre pour n 
            if sum(liste_livre) == testsomme :                                                                                                # Verifie la cohérence des numéros de livre saisie : Si la somme des nombres de la pile liste_livre = à la somme calculé à partir de n alors pas d'incohérence 
            
                ##### Algo verif pile + mot de Dyck #####

                ## Initialisation 


                if min(liste_livre) is liste_livre[0]:                                                                                           # si le plus petit nombre de liste_livre (reverse) est indexé [0] le livre va directement dans listepile_fin 
                    liste_pilefin.append(liste_livre[0]) 
                    mot_de_Dyck.append("A")                                                                                                      # A correspond à un déplacement de liste_livre vers liste_pilemilieu (1 déplacement vers la droite sur le graphique)
                    mot_de_Dyck_int.append(1)                                                                                                    # a A est attribue la valeur 1 qui possède les mêmes propriétes que A mais plus facile de traiter des valeurs numériques
                    mot_de_Dyck.append("B")                                                                                                      # B correspond à un déplacement de liste_pilemilieu vers liste_pilefin (1 déplacement vers la droite sur le graphique)
                    mot_de_Dyck_int.append(0)                                                                                                    # a B est attribue la valeur 0 qui possède les mêmes propriétes que B mais plus facile de traiter des valeurs numériques
                    liste_pilemilieu.insert(0,liste_livre[1])                                                                                    # si condition initiale vraie , on insert directement dans liste_pilemilieu le livre indexé [1] car [0] est en pile_fin (car pour les opérations de comparaison les listes milieu et fin ne doivent pas être vide) 
                    mot_de_Dyck.append("A")
                    mot_de_Dyck_int.append(1)                                                       
                    liste_livre.pop(1)                                                                                                           #  1 car l'indexation ne c'est pas encore réinitialisée  et déplacement de 2 éléments de liste_livre


                else :                                                                                                                           
                    liste_pilemilieu.insert(0,liste_livre[0]) 
                    mot_de_Dyck.append("A")
                    mot_de_Dyck_int.append(1)                                                                                                    # si condition initiale non vérifiée, on insert dans la liste du milieu à la position 0, l'élement indexé [0] de la liste livre (reverse)
                                            
                liste_livre.pop(0)                                                                                                               # que la condition initiale soit vérifiée ou non l'élement de liste_livre indexé 0 sera déplacé vers une aurte pile on le supprime donc de liste_livre


                # note: pour que l'algorithme fonctionne les listes milieu et fin ne doivent jamais être vide avant son arrêt définitif d'ou l'initialisation 

                ## Automatisation
                ## Traitement pour tout les autres éléments à partir minimum du premier éléments exclu ( voir initialisation )

                                    
                while not not liste_livre :                                                                             # tant que la pile liste livre n'est pas vide
                    long = int(len (liste_pilefin)-1)                                                                   # pemet de donner l'indexe (et de le redéfinir à chaque renouvellement de la boucle) de l'élément le plus à droite de la pile fin
        
            
                    if int(liste_pilemilieu[0]) == int(liste_pilefin[long])+1:                                          # si la valeur numérique de l'élément indexé 0 de liste_pilemilieu est égal à la valeur numérique -1 de l'élément indexé [long] de liste_pilefin
                        liste_pilefin.append(liste_pilemilieu[0])                                                       # alors on ajoute à la suite dans liste_pilefin l'élément indexé 0 de liste_pilemileu
                        mot_de_Dyck.append("B")                                                        
                        mot_de_Dyck_int.append(0)                                                        
                        liste_pilemilieu.pop(0)                                                                         # on le supprime alors de la pile milieu car il a été transféré vers la pile fin 
            
                        if not liste_pilemilieu and not not liste_livre:                                                ### 2 BLOC permettant de pallier au probleme de triage de pile dont plusieurs élements sucessif accumulés de liste_pilemilieu n'étaient pas tous envoyés vers liste_pile fin car recoupés par une insertion d'élements provenant de liste_livre à chaque itération : pile du type [5,1,2,3,4], [4,1,2,3,]...   
                            liste_pilemilieu.insert(0,liste_livre[0])                                                   # si la liste_pilemilieu est vide et que la liste_livre ne l'est pas alors on insert dans liste_pilemilieu à la position 0 (car on le pose au dessus de la pile donc au début contrairement à liste_pilefin ou l'on le pose à la suite de la pile) l'élément indexé [0] de liste_livre (reverse)
                            mot_de_Dyck.append("A") 
                            mot_de_Dyck_int.append(1)                                                    
                            liste_livre.pop(0)                                                                          # alors on supprime de liste_livre le livre indexé [0] car déplacé vers pile_milieu 
                        while int(liste_pilemilieu[0]) == int(liste_pilefin[long])+1:                                   # permet de comparer en permanence ( et donc de pallier au problème mentionné plus haut) avant le deplacement d'un élément de liste_livre vers liste_pilemilieu si un ou plusieurs éléments successifs de liste_pilemilieu peuvent être envoyés vers liste_pilefin 
                            liste_pilefin.append(liste_pilemilieu[0])                                                   # ...
                            mot_de_Dyck.append("B")
                            mot_de_Dyck_int.append(0)
                            liste_pilemilieu.pop(0)                                                                         
            

                    else:    
                        if int(liste_pilemilieu[0]) != int(liste_pilefin[long])+1:                                      # Sinon si pas égal on insert le livre indexé [0] de liste_livre dans pile milieu et on recommence
                            liste_pilemilieu.insert(0,liste_livre[0])
                            mot_de_Dyck.append("A")
                            mot_de_Dyck_int.append(1)                                                      
                            liste_livre.pop(0)                                                                             
                            if int(liste_pilemilieu[0]) == int(liste_pilefin[long])+1:                                     # si égale permet de tout de suite orienter cet élement vers liste_pilefin
                                liste_pilefin.append(liste_pilemilieu[0])  
                                mot_de_Dyck.append("B")
                                mot_de_Dyck_int.append(0)                                                
                                liste_pilemilieu.pop(0)
        
                #la boucle s'arrête uniquement quand la pile_livre est vide 


                ###note### : or la pile milieu elle n'est pas forcement vide et peut peut-être encore être triée 
        
                # Finalisation : traitement de la pile milieu ( à ce stade liste_livre est vide, les livres sont soit dans liste_pilemilieu soit dans liste_pilefin)    
            
                while not not liste_pilemilieu:                                                                            # tant que la liste_pilemilieu n'est pas vide                                           
                    long = int(len (liste_pilefin)-1)                                                                      # intègre de nouveau le processus de réitération d'indexation de liste_pilefin dans la boucle (voir plus haut)                                           
                    if int(liste_pilemilieu[0]) == int(liste_pilefin[long])+1:                                             # même procédé de comparaison qu'avant
                        liste_pilefin.append(liste_pilemilieu[0]) 
                        mot_de_Dyck.append("B")
                        mot_de_Dyck_int.append(0)                                                         
                        liste_pilemilieu.pop(0)                                                                            
                    else :                                                                                                 # si liste_pilemilieu ne peut pas être triée arret de la boucle et pile initiale non triable
                        break                                                                                              


                if not liste_livre and not liste_pilemilieu :                                                              # si la liste_livre ET la liste_pilemilieu sont vide, alors la pile est triable
                    print(colored("La pile est triable","green"))                                                       
                else :                                                                                                     # si une des deux au moins ne l'est pas, la pile n'est pas triable
                    print(colored("La pile ne peut pas être triée","red"))                                              

                ## fin algo verif pile

                ##### Mot de Dyck  #####

                mddstr = ' '.join(mot_de_Dyck)                                                                            # permet d'espacer les lettres et enlever virgules et crochet ( affichage plus lisible)
                print("Le mot de Dyck associé à cette pile est : ",colored(mddstr,'yellow'))                                                # affiche le mot de Dyck corespondant à l'utilisateur
                plt.title(str(mddstr))                                                                                    # affiche le mot de Dyck en sous-titre sur la graphique
                ##### Gestion graphique du mot de Dyck #####

                ## Initialistaion : conversion du mot de Dyck en coordonnées

                lines = [(0,0)]                                                                                           # lines est une liste contenenant des uplets correpsondant aux coordonées (x1,y1) des points à tracer, le premier point est commun à tout les mots (origine du repère (0,0))

                if mot_de_Dyck_int[0] == 1 :                                                                              # voir attribution A, B et 0, 1 plus haut. Si l'élement indexé 0 de mot_de_Dyck_int est égal à 1 alors on génère la coorodonée correspondant à un déplacement de 1 unité vers la droite et 0 unité vers le haut 
                    lines.append((1,0))

                else :                                                                                                    # voir attribution A, B et 0, 1 plus haut. Si l'élement indexé 0 de mot_de_Dyck_int est égal à 0 alors on génère la coorodonée correspondant à un déplacement de 0 unité vers la droite et de 1 unité vers le haut 
                    lines.append((0,1))
                mot_de_Dyck_int.pop(0)                                                                                    # on supprime la valeur indexé 0 de mot_de_Dyck_int puisqu'elle à été traitée

                ## Automatisation de la génération des coordonnées de points

                while not not mot_de_Dyck_int :                                                                           # tant que la liste mot_de_Dyck_int n'est pas vide 
                    long = int(len(lines)) - 1                                                                            # permet d'avoir l'index du dernier élément généré
                    if mot_de_Dyck_int[0] == 1 :                                                                          # si l'élément indexé 0 de la liste mot_de_Dyck_int est égal à 1
                        lines.append( lines[long])                                                                        # on ajoute de nouveau la dernières coordonnées générée à la suite de lines pour commencer un nouveau segment
                        lines.append(( lines[long][0] + 1, lines[long][1]))                                               # on ajoute à lines le couple ( abscisse du dernier point généré + 1 , ordonée du dernier point généré ) car déplacement de 1 unité vers la droite par rapport au dernier point)
                        mot_de_Dyck_int.pop(0)                                                                            # on supprime l'élément indexé 0 de mot_de_Dyck_int car traité
                    else :                                                                                                # sinon (car si pas 1 alors 0)
                        lines.append( lines[long])                                                                        # on ajoute de nouveau la dernières coordonnées générée à la suite de lines pour commencer un nouveau segment
                        lines.append(( lines[long][0], lines[long][1] + 1 ))                                              # on ajoute à lines le couple ( abscisse du dernier point généré  , ordonée du dernier point généré +1 ) car déplacement de 1 unité vers le haut par rapport au dernier point)
                        mot_de_Dyck_int.pop(0)                                                                            # on supprime l'élément indexé 0 de mot_de_Dyck_int car traité

                ## fin de la conversion en coordonnées


                # Bloc permettant de convertir les coorodnnées (x1,y1),(x2,y2) de la liste lines en (x1,x2),(y1,y2)
                lines2=[]                                                                                                 # liste servant à contenir les coordonnées réorganisées
                for j in range (0,int((len(lines)/2))):                                                                   # pour j allant de 0 au nombre de couple ( de coordonnées (x,y)) divisé par 2 (car comparaison de couple de coordonnées 2 à 2)
                    j= j*2                                                                                                # j = j x 2 car on traite les couple de coordonnées 2 à 2  
                    lines2.append((lines[0+j][0],lines[1+j][0]))                                                          #  on ajoute à lines2 le couple ( abscisse du couple indexe 0+j de lines , abscisse du couple indexe 1+j de lines ) ( 0+j pour avoir les couples pairs à comparer avec les couples voisins de position impair 1+j (j étant toujours pair))
                    lines2.append((lines[0+j][1], lines [1+j][1]))                                                        #  on ajoute à lines2 le couple ( ordonnée du couple indexe 0+j de lines , ordonée du couple indexe 1+j de lines ) ( 0+j pour avoir les couples pairs à comparer avec les couples voisins de position impair 1+j (j étant toujours pair))
                ###


                ### Choix d'affichage ou non du graphique

                reponsegraph = input(colored("Voulez-vous afficher la représentation graphique du mot de Dyck associé à cette pile ? [Y/n] : ","magenta"))             # intéraction utilisateur


                if reponsegraph == "Y" :
                    for r in range (0,int((len(lines)/2))):                                                                               # pour r allant de 0 au nombre d'élement de lines divisé par 2 
                        r= r*2                                                                                                            # r = r x 2 car traitement des couples 2 par 2 
                        plt.plot(lines2[0+r],lines2[1+r], 'ro',linestyle="-",zorder=10,clip_on=False)                                     # récupère les coorodnnées de lines2 et trace les segments correspondants, les couples étant sous la forme (x1,x2),(y1,y2) les points des abscisses utilisés sont toujours les couple pairs de lines2 et les points des ordonnées sont toujours les couples impairs de lines2, clip_on= False : permet tracer sur le cadre du graphique, Zorder = x , plus x est grand plus la transparence est faible
                    help_button = Button(plt.axes([0.85, 0.05, 0.05, 0.05]),'?',color='darkturquoise')                                    # création du bouton d'aide '?' (permière cordonée : decalage horizontale / 2c : décalage vetrticale / 3c : longeur bouton/ 4c : hauteur bouton )
                    help_button.on_clicked(helptxt)                                                                                       # quadn on clique sur le bouton '?' il appel la fonction helptxt ( voir au début deu programme 'Bouton d'aide')
                    plt.show()                                                                                                            # affiche le graphique
            else :
                print(colored("ERREUR, un ou plusieurs numéro(s) de livre saisi(s) est/sont erroné(s)","red"))


            print("@@@ BOOK STACK SOLVER @@@ by Dr Septimus")
            input(colored("Appuyez sur une touche pour fermer le script et retourner au menu ","blue")) 
            menu()

    ### fin script 2 VERIFICATEUR DE PILE###

####début scrip 1 NB DE POSSIBILITE ###
    elif int(chosen_element) == 1:
            
            
            print("\n")
            print (colored("             .o.                      oooo      .oooo.            .oooo.            .o    oooo","magenta" )) 
            print (colored("             888            Yb        8        .dP""Y88b           .dP""Y88b          o888       8","green" ))
            print (colored(" ooo. .oo.   888             `Yb      8             ]8P'              ]8P'         888       8","magenta" ))
            print (colored(" `888P'Y88b  Y8P    8888888    `Yb    8           .d8P'             <88b.          888       8","green" ))
            print (colored("  888   888  `8'               .dP    8         .dP'                 `88b.         888       8","magenta" ))
            print (colored("  888   888  .o.    8888888  .dP      8       .oP     .o   .o.  o.   .88P  .o.     888       8","green" ))
            print (colored( "o888o o888o  Y8P            dP        8ooo    8888888888   Y8P  `8bd88P'   Y8P    o888o   ooo8","magenta" ))
            print (colored("                                                            '               '                  ","green"))
            print("\n")                                                                                            
            print(colored("@@@ nb de possibilité v 1.2 @@@ by Dr Septimus","red"))                                                                                            
            input("Appuyez sur une touche pour lancer le programme ")
            print("\n")

            
            nl = int(input("Veuillez saisir le nombre de livre (max 519) : "))   #maximum 519
            if nl <= 519 and nl >= 0 :
            
                #print("\n")

                ### Nombre totale de permutations 

                perm = math.factorial(nl)

                ### Calcule le nombre de pile triable

                triable = math.factorial(nl*2) / (math.factorial(nl +1)*math.factorial(nl))                   # formule nombres de Catalan donc démontrée

                ### Calcule le nombre de pile non triable

                #pastriable = math.factorial(nl) - (math.factorial(nl*2))/((math.factorial(nl)**2)*(nl+1))    # formule correcte mais pas prouvée ( ne correspond à aucune suite particulière si ce n'est elle même ) 
                pastriable = int(perm)-int(triable)

                print("Pour une pile de",colored(nl, "yellow"),"livres, il y a",colored(int(triable),"green"),"combinaisons triables et",colored(int(pastriable),"red"),"combinaisons non triables pour un total de",colored(perm,"yellow"),"combinaisons possibles" )
                print("\n") 
                
            else :
                print(colored("ERREUR","red"),"veuillez saisir un nombre compris entre 0 et 519")
                print("\n")
            print("@@@ nb de possibilité v 1.2 @@@ by Dr Septimus")
            input(colored("Appuyez sur une touche pour fermer le script et retourner au menu ","blue"))
            menu()
            
            
            ### fin du script 1 NB DE POSSIBILITE ###
        

    elif int(chosen_element) == 3:
            print(colored("MAXIPILE HELPER version 1.6 ","green", 'on_cyan'))
            print(colored("by Dr Septimus","white",'on_cyan'))
            print(colored("MEJ 2022","white",'on_cyan'))
            print(colored("Fermeture du programme",'red'))
           
            sys.exit()
    
    
        
       


    
    
    else:
            print(colored('TU NE SAIS PAS LIRE ?',"red","on_green"))
            input("Appuyez sur une touche pour retourner au menu")
            menu()
    
        
menu()

