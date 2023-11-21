<!--
-------------------------------------------------------------------------------
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-------------------------------------------------------------------------------
-->

<!-- .slide: class="slide-title" data-background-image="assets/title-slide.svg" data-background-color="#000000" data-background-size="contain" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<h1 id="talk-title">
  Campos magnéticos, <br>de escala microscópica <br> a continental
</h1>
<p id="talk-authors">
  <a href="https://www.leouieda.com" id="talk-speaker">Leonardo Uieda</a>
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="row talk-info">
<div class="col-large">

<i class="fa fa-calendar-alt" style="margin: 0 10px 0 0"></i>
21 Novembro 2023
<span style="margin: 0 20px"></span>
Por Dentro Da Geofísica / IAG-USP

<!-- Permission to reuse and CC-BY license logo -->
<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Feel free to screenshot/share/reuse this presentation
<span style="margin: 0 20px"></span>
<a href="https://creativecommons.org/licenses/by/4.0/"><i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>CC-BY 4.0 License</a>

</div>
<div class="col-medium">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
  <a href="https://www.compgeolab.org"><img src="assets/compgeolab-banner-light.svg" alt="Computer-Oriented Geoscience Lab"></a>
  <a href="https://www.iag.usp.br/"><img src="assets/iag.png" alt="Instituto de Astronomia, Geofísica e Ciências Atmosféricas"></a>
  <a href="https://www.usp.br/"><img src="assets/usp.png" alt="Universidade de São Paulo"></a>
</div>
</div>

</div>
</div>

===============================================================================

<!-- .slide: class="slide-transition" -->

# Conheça seu palestrante

===============================================================================

<!-- .slide: data-background-video="assets/brasil-sao-paulo-rio.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote">

Bacharelado (USP) | Mestrado e Doutorado (Observatório Nacional)

</div>

===============================================================================

<!-- .slide: data-background-image="assets/paleomagnetism-field-work.jpg" data-background-size="contain"  -->

<div class="r-stretch">
</div>
<div class="footnote">

IC em paleomagnetismo (orientador Manoel D'Agrella)

</div>

===============================================================================

<div class="r-stretch centered">
<div>

<img src="assets/tesseroids.svg" style="margin-bottom: 5%;">

Programas em C para modelagem grav na esfera

[`tesseroids.leouieda.com`](https://tesseroids.leouieda.com)

</div>
</div>
<div class="footnote">

IC \#2 + TCC em gravimetria (orientadora Naomi Ussami)

</div>

===============================================================================

<div class="centered r-stretch">
<div style="width: 100%; height: 100%">
<video style="width: auto; height: 100%" muted data-autoplay>
<source data-src="assets/planting-inversion.mp4" type="video/mp4"/>
</video>
</div>
</div>
<div class="footnote-left">

Mestrado e Doutorado em inversão (orientadora Valéria C.F. Barbosa)
<br>
Método de plantação para inversão 3D ([Uieda & Barbosa, 2012](https://doi.org/10.1190/geo2011-0388.1))

</div>

===============================================================================

<!-- .slide: data-background-image="assets/fatiando-banner.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">

</div>

<div class="huge">

**Fatiando a Terra**

</div>

Bibliotecas em Python para modelagem, inversão e processamento

[www.fatiando.org](https://www.fatiando.org)

===============================================================================

<!-- .slide: data-background-video="assets/seismic-waves-demo.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote dark">

Ensinando geofísica na geologia da UERJ com Python + Jupyter + Fatiando

</div>

===============================================================================

<!-- .slide: data-background-video="assets/run-away-to-hawaii.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote">

Professor Visitante na University of Hawaiʻi at Mānoa

</div>

===============================================================================

<div class="r-stretch centered">
<div>
<img src="assets/gmt.png" style="width: 60%;">

Programas em C muito utilizados na geofísica (processamento e mapas)

Fui para criar o **PyGMT**

[www.pygmt.org](https://www.pygmt.org)

</div>
</div>
<div class="footnote">

Projeto coordenado pelo Paul Wessel

</div>

===============================================================================

<!-- .slide: data-background-image="assets/uh-manoa.jpg" data-background-size="contain"  -->

<div class="r-stretch">
</div>
<div class="footnote dark">

Vista da minha sala na UH em direção ao vale de Manoa (sempre tinha um arco-íris)

</div>

===============================================================================

<!-- .slide: data-background-video="assets/hawaii-to-liverpool.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote">

Fui para a University of Liverpool com o cargo de Lecturer in Geophysics

</div>

===============================================================================

<!-- .slide: data-background-video="assets/remote-teaching-demo.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote">

Aprendendo a ser YouTuber durante a pandemia

</div>

===============================================================================

<!-- .slide: data-background-video="assets/liverpool-to-usp.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote">

Em 2023, voltei para o IAG-USP como Professor Doutor no Departamento de Geofísica

</div>

===============================================================================

<!-- .slide: class="slide-transition" -->

# Voltando ao tema da palestra

Campos magnéticos, de escala microscópica a continental

===============================================================================

<div class="enormous">

<i class="fas fa-microscope"></i>

</div>
<div class="small fragment">

**Aluno:** Gelson F. Souza Junior
<br>
**Colaboradores:** Ricardo Trindade, Roger Fu, Janine Carmo

</div>

===============================================================================

<!-- .slide: data-background-image="assets/paleomagnetic-rock-sample.jpg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch centered">

</div>
<div class="footnote">

Amostra de rocha para uso em paleomagnetismo

</div>

===============================================================================

<!-- .slide: data-background-image="assets/classic-molspin-magnetometer.jpg" data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote">

Magnetômetro que eu usei durante minha IC em paleomagnetismo

</div>

===============================================================================

<div class="r-stretch centered">
<div>
<img src="assets/qdm-sketch.jpg">
</div>
</div>
<div class="footnote">

Quantum Diamond Microscope (QDM).
Fonte: [Glenn et al. (2017)](https://doi.org/10.1002/2017GC006946)

</div>

===============================================================================

<div class="r-stretch centered">
<div style="width: 100%">
<img src="assets/micromag-data.jpg" style="width: 70%">
</div>
</div>
<div class="footnote">

Fonte: [Souza Junior et al. (2023)](https://doi.org/10.31223/X5QD5Z) (CC-BY)

</div>

===============================================================================

<div class="r-stretch centered">
<div style="width: 100%">
<img src="assets/micromag-tga.jpg" style="width: 70%">
</div>
</div>
<div class="footnote">

Fonte: [Souza Junior et al. (2023)](https://doi.org/10.31223/X5QD5Z) (CC-BY)

</div>

===============================================================================

<div class="r-stretch centered">
<div style="width: 100%">
<img src="assets/micromag-stretch.jpg" style="width: 70%">
</div>
</div>
<div class="footnote">

Fonte: [Souza Junior et al. (2023)](https://doi.org/10.31223/X5QD5Z) (CC-BY)

</div>

===============================================================================

<div class="r-stretch centered">
<div style="width: 100%">
<img src="assets/micromag-detect.jpg" style="width: 70%">
</div>
</div>
<div class="footnote">

Fonte: [Souza Junior et al. (2023)](https://doi.org/10.31223/X5QD5Z) (CC-BY)

</div>

===============================================================================

<div class="r-stretch centered">
<div style="width: 100%">
<img src="assets/micromag-euler.jpg" style="width: 65%">
</div>
</div>
<div class="footnote">

Fonte: [Souza Junior et al. (2023)](https://doi.org/10.31223/X5QD5Z) (CC-BY)

</div>

===============================================================================

<div class="r-stretch centered">
<div style="width: 100%">
<img src="assets/micromag-inversion.jpg" style="width: 65%">
</div>
</div>
<div class="footnote">

Fonte: [Souza Junior et al. (2023)](https://doi.org/10.31223/X5QD5Z) (CC-BY)

</div>

===============================================================================

<div class="r-stretch centered">
<div style="width: 100%">
<img src="assets/micromag-stereo.jpg" style="width: 65%">
</div>
</div>
<div class="footnote">

Fonte: [Souza Junior et al. (2023)](https://doi.org/10.31223/X5QD5Z) (CC-BY)

</div>

===============================================================================

<div class="enormous">

<i class="fas fa-globe-americas"></i>

</div>
<div class="small fragment">

**Aluna:** India Uppal
<br>
**Colaboradores:** Richard Holme, Vanderlei C. Oliveira Jr.

</div>

===============================================================================

<!-- .slide: data-background-image="assets/antarctica-warming.jpg" data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote">

Fonte: [NASA Earth Observatory](https://earthobservatory.nasa.gov/images/36736/antarctic-warming-trends) (public domain)

</div>

===============================================================================

<!-- .slide: data-background-image="assets/antarctica-heatflow-direct.jpg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote dark">

Fonte: [Burton-Johnson et al. (2020)](https://doi.org/10.5194/tc-14-3843-2020)

</div>

===============================================================================

<!-- .slide: data-background-image="assets/antarctica-magnetic-data.jpg" data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote-left">

Fonte: India Uppal (CC-BY)
<br>
From APMAP2 data ([Golynsky et al., 2018](https://doi.org/10.1029/2018GL078153)) (CC-BY)

</div>

===============================================================================

<div class="centered r-stretch">
<div class="large">

<p>
<!-- .element: class="fragment" data-fragment-index="1" --> Dados magnéticos
</p>
<p>
<!-- .element: class="fragment" data-fragment-index="2" --> 
<i class="fas fa-arrow-alt-circle-down" style="color: #0053d1"></i> 
<br>
Profundidade máxima das fontes<sup>1</sup>
</p>
<p>
<!-- .element: class="fragment" data-fragment-index="3" --> 
<i class="fas fa-arrow-alt-circle-down" style="color: #0053d1"></i> 
<br>
Profundidade da isoterma de 580°C<sup>2</sup>
</p>
<p>
<!-- .element: class="fragment" data-fragment-index="4" --> 
<i class="fas fa-arrow-alt-circle-down" style="color: #0053d1"></i> 
<br>
<strong>Fluxo de calor na superfície</strong><sup>3</sup>
</p>

</div>
</div>
<div class="footnote fragment" data-fragment-index="2">

<span class="fragment" data-fragment-index="2"><sup>1</sup> Assumindo magnetização homogenea e induzida.</span>
<br>
<span class="fragment" data-fragment-index="3"><sup>2</sup> Assumindo que os minerais magnéticos são magnetita.</span>
<br>
<span class="fragment" data-fragment-index="4"><sup>3</sup> Assumindo condutividade térmica homogenea.</span>

</div>

===============================================================================

<!-- .slide: data-background-image="assets/magnetic-spectrum-method-window.svg" data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote-left">

Fonte: [Burton-Johnson et al. (2020)](https://doi.org/10.5194/tc-14-3843-2020)

</div>

===============================================================================

<!-- .slide: data-background-image="assets/magnetic-spectrum-method-full.svg" data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote-left">

Fonte: [Burton-Johnson et al. (2020)](https://doi.org/10.5194/tc-14-3843-2020)

</div>

===============================================================================

<!-- .slide: data-background-image="assets/heatflow-model-comparison.svg" data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote-left">

Fonte: [Lösing et al. (2020)](https://doi.org/10.3389/feart.2020.00105)

</div>

===============================================================================

<div class="huge">

Métodos espectrais

<img src="assets/magnetic-spectrum-method.svg" style="width: 50%">

<div class="fragment">

possuem **sérios problemas**

<div class="normalsize">

[Audet & Gosselin (2019)](https://doi.org/10.1093/gji/ggz166) |
[Núñez Demarco et al. (2021)](https://doi.org/10.1093/gji/ggaa361) |
[Szwillus et al. (2022)](https://doi.org/10.1093/gji/ggac133)

</div>

</div>

</div>

===============================================================================

<div class="centered">
<div>

<img src="assets/airborne-plus-satellite.jpg" style="width: 90%">

<div class="small">

Ex: [Martos et al., (2017)](https://doi.org/10.1002/2017GL075609), 
[Kim et al. (2022)](https://doi.org/10.1029/2021JB023329) 

</div>

</div>
</div>
<div class="footnote">

Mapa da direita modificado de: [Fox Maule et al. (2005)](https://doi.org/10.1126/science.1106888)

</div>

===============================================================================

<div class="huge">

**Fontes equivalentes**

<div class="small">
<span class="fragment">~regressão em aprendizagem de máquinas</span>
</div>

</div>
<div class="large" style="margin-top: 2em">

<span class="fragment">De **~50k** dados em **dias** com  <i class="fas fa-server"></i> <i class="fas fa-server"></i> </span>

<span class="fragment">a **~10G** dados em **horas** com <i class="fas fa-laptop"></i></span>

</div>

===============================================================================

<div class="r-stretch centered">
<div>
<img src="assets/hamed-inputs.jpg">
</div>
</div>
<div class="footnote-left">

From the BSc dissertation of Hamed Rashid Hamed Alsalehi (2022)

</div>

===============================================================================

<div class="r-stretch centered">
<div>
<img src="assets/hamed-grids.jpg">
</div>
</div>
<div class="footnote-left">

From the BSc dissertation of Hamed Rashid Hamed Alsalehi (2022)

</div>

===============================================================================

<!-- .slide: data-background-image="assets/india-results.svg" data-background-size="contain" -->

<div class="r-stretch">
</div>
<div class="footnote-left">


From the poster presentation: [Uppal et al. (2023)](https://www.compgeolab.org/news/pgr-conference2023.html)

</div>

===============================================================================

# **Objetivos finais**

<div class="large">

1. <!-- .element: class="fragment" --> <strong>Dados</strong> magnéticos Antárticos aéreo + satélite
1. <!-- .element: class="fragment" --> <strong>Método</strong> atualizado de inversão de fluxo geotermal
1. <!-- .element: class="fragment" --> <strong>Software livre</strong> que implementa tudo isso
1. <!-- .element: class="fragment" --> <strong>Aplicações</strong> a outros continentes

</div>

===============================================================================

<!-- .slide: class="slide-transition" -->

# Resumindo

===============================================================================

<div class="large">

1. <!-- .element: class="fragment" --> Microscopia + Geofísica aplicada + Proc. imagens = <strong>Micropaleomagetismo</strong>
1. <!-- .element: class="fragment" --> Inferência de fluxo geotermal é difícil
1. <!-- .element: class="fragment" --> Fontes equivalentes FTW!
1. <!-- .element: class="fragment" --> Muito a fazer para inversão do fluxo geotermal

</div>

===============================================================================

# **Trabalho apresentado de:**

<div class="row">
<div class="col-gutter">

<img src="https://github.com/indiauppal.png" style="border-radius: 50%;
  box-shadow: 0px 0px 25px -5px #333333; width: 50%;">

## India Uppal 

(PhD @ U. of Liverpool)

</div>
<div class="col-gutter">

<img src="https://github.com/Souza-junior.png" style="border-radius: 50%;
  box-shadow: 0px 0px 25px -5px #333333; width: 50%;">

## Gelson F. Souza Junior

(PhD @ IAG-USP)

</div>
</div>

===============================================================================

<div class="huge">

**Afim de uma IC?**

Venha conversar!

</div>

===============================================================================

<!-- .slide: class="slide-contact" data-background-image="assets/contact-slide.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch centered">
<div>

<i class="fas fa-comments"></i>
<br>
Contact:
<a href="https://www.leouieda.com">www.leouieda.com</a>

<i class="fab fa-github"></i>
<br>
Source code for this presentation:
<br>
[github.com/leouieda/por-dentro-geofisica-2023](https://github.com/leouieda/por-dentro-geofisica-2023)

<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
<br>
Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>
<div class="footnote-left dark">

The background image is a Landsat 9 scene of the city of São Paulo, Brazil,
showing the USP campus in the center.

</div>
