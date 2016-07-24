---
layout: default
title: WFS Booster
id: wfsbooster
---

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}  

WFS Booster er den smarte måde at arbejde med kort
 WFS henter alle relevante kort via internettet direkte fra de officielle kilder. Det sker på én gang, og du får kortene direkte ind i MicroStation, Bentley Navigator eller Bentley Map. Du er fri for at hente kortoplysninger hos hver enkelt kilde, og du er fri for at spekulere på, om alle data er opdaterede. 

WFS Booster henter kort direkte fra
Kortforsyningen
ArealInfo
Plansystem Dk
PLF (Skel under tilblivelse)

Du kan hente matrikelkort, bygninger, husnumre, veje, bygge- og beskyttelseslinjer, fredninger, naturbeskyttelse, lokalplaner og kommuneplaner direkte ind i MicroStation som grafiske elementer.

WFS Booster henter data i GML format, så alle data indeholder både geometri og attributter. Attributter kan enten vises på de grafiske elementer som tags eller userdata. Det vil sige, at du fx kan se KMS journalnumre på skel, beskrivelse af beskyttede naturtyper eller åbne link til PDF lokalplaner direkte fra MicroStation.

Fordele med WFS Booster
Alle kort er 100 % ajourført
Download matrikelkort, lokalplaner osv. i ét klik.
Oplysninger kommer fra alle udbydere på én gang
Vektorkort med attributter
Alle oplysninger placeres i dit kort i MicroStation.
Pdf-filer med lokalplaner ses som hyperlink på kortet.
Færdigt arbejde – med ajourførte kortoplysninger!
 
Dit udbytte:
Tidsbesparende ved alle kortlægningsopgaver
Brugervenligt system med tilfredse brugere
Sikkerhed for korrekte informationer
Tryghed for et validt kort som beslutningsgrundlag
Kunderne får en bedre og hurtigere service
Giver konkurrencefordele på både kvalitet og prissætning

