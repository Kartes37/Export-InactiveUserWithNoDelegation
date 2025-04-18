# Export-InactiveUserWithNoDelegation

Ce script PowerShell permet d’identifier les boîtes aux lettres partagées associées à des comptes désactivés dans Azure AD qui n'ont aucune délégation (Full Access).
Il se connecte à Azure AD et à Exchange Online, récupère les utilisateurs désactivés, vérifie s’ils ont une boîte aux lettres partagée, puis liste celles qui n'ont aucun utilisateur ayant des droits d'accès complets.
Les résultats sont affichés dans la console et exportés dans un fichier CSV pour analyse ultérieure.
