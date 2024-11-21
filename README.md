[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17264866&assignment_repo_type=AssignmentRepo)
# bemen
Bemen repo for Victor Naranjo

# Comit 1
cambi al color de la capcelera `<tr bgcolor="blue">` i aplicar el template `<?xml-stylesheet type="text/xsl" href="cataleg.xslt"?>`
# Comit 2
afegir un filtre al xslt `<xsl:for-each select="catalog/cd[country='USA']">` i la seva etiqueta `<th style="text-align:left">Country</th>`
# Comit 3
eliminem el filte i fem un sort per artist `<xsl:for-each select="catalog/cd"><xsl:sort select='artist'/>`
# Comit 4
Mostrem els cds que tenen un preu menor a 10 `<xsl:for-each select="catalog/cd[ price &lt; 10 ]">`
# Comit 5
Utilitzant un if fem que els cds que tinguin un preu de 10 o més tinguin un gomet vermell i els de menys un verd `<td style="text-align:center"> <xsl:if test="price &lt; 10">🟢</xsl:if> <xsl:if test="price &gt; 10">🔴</xsl:if></td>`
# Comit 6
fem el mateix que en el comit 5 l'nic que utilitzem l'etiqueta chose `<xsl:choose><xsl:when test="price &lt; 10">🟢</xsl:when><xsl:when test="price &gt; 10">🔴</xsl:when></xsl:choose>`
