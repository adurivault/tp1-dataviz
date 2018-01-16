# Data Visualisation : Radar Chart

## Introduction
Node-link diagrams, also called graphs, or network diagrams, are diagrams that display connection between different elements. The graph consists of a set of nodes, some of which are connected with vertices.
The nodes of the node-link diagram represent the different elements that are studied. They are displayed on a plane, most often represented as bubbles of colors. If a "connexion" exists between two of these elements, we draw a vertice between them.

<table border="0">
  <tr>
    <td>
      <img src="img/Illustration.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      First example of a node-link diagram [1]
    </td>
  </tr>
</table>


## Different forms

A lot of variants exist of node-link diagrams. Here are a few elements that can vary and make it interesting to study :

***Position of nodes on the plane***

If the nodes a positionned randomly on the plane, the data can be hard to interpret because of the entanglement of the connexions between the nodes. In order to avoid this, the positionning of the different elements on the plane can be done in a various number of ways :

- Force-based visualisation:
This method is based on physics and mathematics : we modelise a repulsion force between the nodes (such as a magnetic force between two particles positvely charged : the closer the nodes, the greater the force), as well as an attraction force between two connected particule (such as a spring : the further the nodes, the stronger the force). The system is then unleashed, and we can display the system at rest. Physics are well made, and this gives a pretty good results which intuitively minimises the size of the connections, without crushing everything together.
Sometimes, these graphs are displayed in a dynamic system that make it possible to interact with the nodes: by dragging one node with the mouse, the graph rearranges itself based on the forces, which allows a nice user-experience.

<table border="0">
  <tr>
    <td>
      <img src="img/Force_based_visualisation_2.jpg" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Example of force based positionnement of nodes [2]
    </td>
  </tr>
</table>


- Circle
Another possible way of positionning the node is to display them in a circle, and have all the connections inside the circle. This makes it relatively easy to read, since all connections do not overlap with nodes. Most of the time it is coupled with colors of the nodes and the connections, which makes beautiful representations.
Below is an example where nodes represent the stations of a bike-sharing system in Boston, and the connections represents the trips between these stations.

<table border="0">
  <tr>
    <td>
      <img src="img/circle-visualisation-boston.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Example of cirlce-positionned nodes : Boston bike-sharing system.[3]
    </td>
  </tr>
</table>

-3D :
Finally, some link-nodes diagrams are represented in 3D space. This, in theory, allows a more compact representation of data, with more connections that would not intersect. However, this is alwys displayed on a 2D screen, and this makes it less of an advantage. Moreover, even with a dynamic user interface which lets us interact with the data, rotate it, etc.. Thhe result loses in clarity.

Addition features:
It ios possible to add additional information to a node-link diagram in numerous ways :

- Size of bubbles:
The size of the bubbles can be used to display a quantitative infrmation concerning the nodes.

- Size of the links:
The width of the links is also a nice and intuitive way to display information concerning the importance of the connection between two nodes. This is used in the bike-sharing ystem reprenstation above, where the size of the links is related to the number of trip between the 2 stations.


## Utilisation & Exemples connus

Node-link duagrams have an important case study : social networks. Indeed, it is interesting to represent a graph of social network with nodes symbolising users of the network, and links connected users, such as "friends" on Facebook.

<table border="0">
  <tr>
    <td>
      <img src="img/social-network.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Example of social-network Visualisation [4]
    </td>
  </tr>
</table>



## Critiques

### Advantages

* Visualisation globale aisé et naturelle : utilisation simultanée de forme, d'angle et d'air
* Possibilité de comparer les valeurs des variables (cercle équipotentiel)
* Comparaison de plusieurs individus

### Drawbacks

* Nombre limité d'individus pouvant être comparé simultanément
* Nécessite une échelle commune (ou utilisation d'échelle absolue, ie on ne peut pas comparer des °C et des €)
* Le nombre de variable utilisable est borné : minoré par 3 (par construction géométrique) et majoré par 10 (par souci de lisibilité).


## Sources

* [1] First example of a Node-Link diagram: http://www.orangetreeglobal.com/common-type-data-visualisations-examples/
* [2] Force based positionnement of nodes : https://medium.com/@mbostock/a-better-way-to-code-2b1d2876a3a0
* [3] Marketing Data Viza : http://dev.assets.neo4j.com.s3.amazonaws.com/wp-content/uploads/2012/10/hubway_lg.png?_ga=2.110268741.1913023441.1516114120-918224082.1516114120
* [4] Social network graph : https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/data-visualization-for-human-perception
* [4] Human ressources Radar Chart : http://www.mclarensolutions.com/wp-content/uploads/2011/01/tcfdepartmentalaverage.jpg
* [5] Utilisation dans Fifa18 : https://indicadoresportivo.com/wp-content/uploads/2017/09/fifa18_radarchart.png
internet 2010 :
http://www.opte.org/the-internet/
