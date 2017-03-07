---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
#  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Notre EPN"
  url: '/pages/Notre-EPN/'
  image: widget-1-302x182.jpg
  text: 'La B@se est un Espace Public Numérique créé par l’association Cyber Emploi Drôme Ardèche et situé en centre-ville à Valence. Nous faisons aussi partie du réseau Cyberbase. Nous essayons de contribuer à la réduction de le « fracture numérique » en aidant les personnes les + éloignées de l’usage de ces technologies pour diverses raisons notamment financières, à se les approprier.'
widget2:
  title: "Espace Public Internet ?"
  url: '/pages/Espace-Public-Internet/'
  image: widget-2-302x182.jpg
  text: 'Les EPI (Espaces Publics Internet) sont vos espaces d’accès et de sensibilisation aux usages numériques. Initiez-vous aux outils informatiques, connectez-vous à Internet, découvrez les possibilités que vous offre le numérique, quels que soient vos besoins et envies. Les EPI, ce sont aussi des espaces de vie, favorisant le rapprochement et l’échange, la découverte et les connaissances…'
widget3:
  title: "Page Facebook"
  url: 'http://www.facebook.com/epnlabasevalence/'
#  image: widget-github-303x182.jpg
  text: '<iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FEPN-La-Base-Formations-Solidaires-386282618245673&tabs=timeline&width=340&height=500&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=false&appId" width="340" height="500" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"></iframe>'

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
