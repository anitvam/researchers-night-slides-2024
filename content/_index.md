+++
title = "Ecosistemi coordinati di robot programmabili"
outputs = ["Reveal"]
+++

<script>
  $(document).ready(function() {
    
   function animaImmagine(idName) {
        $(idName).animate({
            width: '+=50px',
            height: '+=50px'
        }, 1000, function() {
            $(idName).animate({
                width: '-=50px',
                height: '-=50px'
            }, 1000, function() {
                // Ripeti l'animazione in loop
                animaImmagine(idName);
            });
        });
    }

    animaImmagine("#robot1");
    animaImmagine("#robot2");

  });

  
</script>

# Ecosistemi coordinati <br/>di robot programmabili


<img src="example-background.svg" width="25%" class="my-5" />

<div style="font-size: 0.8em">
Gianluca Aguzzi, Martina Baiardi, Roberto Casadei,  Angela Cortecchia, <br/>
Davide Domini, Nicolas Farabegoli, Danilo Pianini, Mirko Viroli
</div>

<img src="images/robot-1.svg" width="15%" id="robot1" style="position: absolute; top: 0%; left: 2%;" />
<img src="images/robot-2.svg" width="10%" id="robot2" style="position: absolute; bottom: 0%; right: 8%;" />

---



{{% multicol %}}{{% col class="text-right" %}}

<img src="images/animal-1.jpg" width="700px" style="margin-right: 18px"/>

{{% /col %}}{{% col class="text-left" %}}

<img src="images/animal-2.webp" width="700px" style="margin-left: 18px"/>

{{% /col %}}{{% /multicol %}}

{{% multicol %}}{{% col class="text-right" %}}

<img src="images/animal-3.jpg" width="700px" style="margin-right: 18px"/>


{{% /col %}}{{% col class="text-left" %}}

<img src="images/image-4.jpeg" width="700px" style="margin-left: 18px" />

{{% /col %}}{{% /multicol %}}


    
---


<iframe width="100%" height="1000px" loading="eager" autoplay="true" src="https://lumasky.show/wp-content/uploads/personal/oblozhka2.html?autoplay=1&controls=0&loop=1&modestbranding=1&mute=1&showinfo=0" ></iframe> 

---

<iframe width="100%" height="900px" loading="eager" autoplay="true" src="https://www.youtube.com/embed/qy4_3qJbLeA?si=P2jwvfj6-YR9CujO?autoplay=1" frameborder="0"></iframe>

---

## Una piccola dimostrazione

{{% multicol %}}{{% col class="text-center" %}}

<img src="images/robot.png" width="80%"/>

{{% /col %}}{{% col class="text-left" %}}

Abbiamo un robot speciale chiamato **leader**, che *guida* gli altri, ottenendo un **sistema auto-organizzante**:

1. Tutti i robot puntano verso la stessa direzione
2. Tutti i robot puntano verso il leader
3. I robot "danzano" in modo coordinato, raggiungendo la stessa direzione puntata dal leader
4. Formazioni di semplici strutture: tutti i robot si dispongono in linea e in cerchio rispetto al leader.

{{% /col %}}{{% /multicol %}}

---

# Un nostro simulatore: MacroSwarm

<p align="center">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224010877-6f5c9d36-d348-4343-8b66-19f78778297e.gif">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224012332-290c81e1-effa-4cab-ae03-c603c116dd99.gif">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224012411-fbef5948-c546-49fa-b411-f5662831ef1b.gif">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224010942-178aea25-0fde-4bdd-b0e9-59709640cc30.gif">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224011009-411449cb-2b8e-4ebf-bc00-6fa8ba7a9120.gif">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224012578-d375de46-23c3-44e6-99cf-9d937548a1a5.gif">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224012699-0e29f217-66fb-44e7-b86e-85f6265e695e.gif">
      <img width=20% src="https://user-images.githubusercontent.com/23448811/224012742-b765aa73-dd31-4ffb-91a3-93c06e8b2750.gif">
</p>

--- 

## Chi siamo?

{{% multicol %}}

{{% col class="text-left" %}}
<img src="https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=355340&IdFoto=e3a7b911" style="width:15%">
<b>Mirko Viroli</b> - <em>Professore Ordinario</em> </br>

<img src="https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=503326&IdFoto=e1c80103" style="width:15%">
<b>Danilo Pianini</b> - <em>Professore Associato</em> </br>

<img src="https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=649232&IdFoto=4ba13386" style="width:15%">
<b>Roberto Casadei</b> - <em>Professore Associato</em> </br>

<img src="https://avatars.githubusercontent.com/u/23448811?v=4" style="width:15%">
<b>Gianluca Aguzzi</b> - <em>Post Doc</em></br>
{{% /col %}}

{{% col class="text-left" %}}
<img src="https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1135878&IdFoto=7e5aea53" style="width:15%">
<b>Martina Baiardi</b> - <em>Dottoranda</em> </br>

<img src="https://avatars.githubusercontent.com/u/85068744?v=4" style="width:15%">
<b>Angela Cortecchia</b> - <em>Dottoranda</em></br>

<img src="https://avatars.githubusercontent.com/u/68516023?v=4" style="width:15%">
<b>Davide Domini</b> - <em>Dottorando</em></br>

<img src="https://www.unibo.it/uniboweb/utils/UserImage.aspx?IdAnagrafica=1057398&IdFoto=d40837ab" style="width:15%">
<b>Nicolas Farabegoli</b> - <em>Dottorando</em>

{{% /col %}}

{{% /multicol %}}

--- 

## Cosa facciamo?

- Sistemi adattivi auto-organizzanti 
- Intelligenza artificiale distribuita
- Ingegneria di sistemi distribuiti complessi
- Pervasive computing
- Esplorazione di nuovi paradigmi e linguaggi di programmazione
- Internet of Things
- Edge computing