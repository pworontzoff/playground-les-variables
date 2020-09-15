# Exercice 4

Dans l’optique de développer une app pour smartphone permettant de localiser le DEA (Défibrillateur Externe Automatisé) le plus proche de vous et ainsi de peut-être sauver des vies, nous allons développer un prototype permettant de tester l’idée. Dans la problématique, il est nécessaire de pouvoir calculer la distance entre deux points du globe. Ecrivez en C un programme permettant de calculer une distance à partir de coordonnées GPS. Pour l’exercice, utilisez les formules suivantes :

```math
x = (longitudeB - longitudeA) \times \cos \left(\frac{latitudeA + latitudeB}{2} \right)
```

```math
y = latitudeB - latitudeA
```

```math
d = \sqrt{x^2 + y^2} \times 6371
```

**Note :** Dans cette formule, les latitudes et longitudes sont exprimées en radians.
La formule donne la distance en km entre les 2 points.
Les calculs peuvent être vérifiés facilement avec Google Maps.