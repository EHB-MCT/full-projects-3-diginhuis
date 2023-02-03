
# Klant - Kunst In Huis

Kunst in Huis werkt als een bibliotheek waar iedereen kunstwerken kan lenen. Een ideale formule om het boeiende werk van hedendaagse Vlaamse kunstenaars te ontdekken en in je eigen huis te hangen. 

De collectie van Kunst in Huis telt vandaag zo'n 5.000 werken van 400 actuele kunstenaars die wonen en werken in Vlaanderen. De collectie wil een beeld geven van alle hedendaagse beeldende kunststromingen in Vlaanderen. Regelmatig verrijken we de collectie met nieuwe kunstenaars en kunstwerken.

Kunst in Huis heeft vijf filialen waar je kunt inschrijven, kiezen, reserveren, ruilen en kopen. Je vindt ons in Antwerpen, Brussel, Gent, Kortrijk en Leuven.

Op die manier maakt Kunst in Huis een brede waaier aan hedendaagse kunstvormen toegankelijk en geven we beginnende kunstenaars een duw in de rug. Bovendien wordt een kunstwerk nooit ‘alleen maar’ uitgeleend, maar krijg je ook het verhaal van de kunstenaar mee wanneer je een werk ontleent.


# Team - Dimetrodon

- Lead Back-End Developer: [@AliAmrani](https://github.com/EdiciusPenguin)
- Front-End Developers: [@AachalShrestha](https://github.com/AachalShrestha) & [@DmitrCambur](https://github.com/DmitrCambur)
- Designer & Editor: [@StephenAsante](https://github.com/Stephenasante21) & [@NailMaimouni](https://github.com/nailmaimouni)
- Physical Prototype Creator: [@ZaidZobair](https://github.com/ZaidZobair)




# Dependencies

 - [swiperjs](https://swiperjs.com)
 - [css-loader](https://www.npmjs.com/package/css-loader)
 - [js-cookie](https://www.npmjs.com/package/js-cookie)
 - [lightpick](https://www.npmjs.com/package/lightpick)
 - [lodash](https://www.npmjs.com/package/lodash)
 - [qr-scanner](https://www.npmjs.com/package/qr-scanner)
 - [socket.io](https://www.npmjs.com/package/socket.io)
 - [style-loader](https://www.npmjs.com/package/style-loader)
 - [sweetalert2](https://www.npmjs.com/package/sweetalert2)
 - [three](https://www.npmjs.com/package/three)


# Deployment

- Back-End part of the application cannot be ran locally.

- Pull and deploy the project afterwards with these commands in the Terminal:

```bash
  npm install  
```
```bash
  +
```
```bash
  npx webpack
```


## Used Services
As for services we make use of https://render.com/ to host our backend & websocket.
We also make use of https://www.ovh.com/ to host both our files & static website, which
should be available at http://kader.kunstinscherm.be/ .


# Kunst In Scherm - Web Application

## Homepage
The homepage consists of 2 pages, the unregistered and registered page. 

The unregistered page gets greeted with the title "Featured Digital Art" and 2 sliders with 6 art pieces generated from the Database in each slider.

The registered page consists of 2 titles with 2 sliders each. The first title is "These are your recommended artworks, based on what you've viewed before." where the sliders exist of art pieces that are generated based on what the user browsed. The second title is "These have recently been added to the Kunst In Scherm collection.". These sliders consists of recently added art pieces.

## Gallery

Gallery begins with a filter button and a search textblock. The user can properly filter their tastes such as Style, Type and Topic. The gallery will then generate the proper art pieces based on the tags selected in the filter section.

If the user wishes to search more specifically then he or she is welcomed to use the textblock to search the artist or artwork name.

## Frames

The frames page is where you are able to add a frame/screen.

The user begins by pressing the "+" on the right and he or she will be greeted with an instruction screen on how to set up a frame/screen.

The user will then scan the QR-code that has been presented on the screen.

After that the user will have to give the frame/screen a name and set a location for it.


When the frame/screen has been added. The user will have the ability to click on the settings icon to select which art he or she wants to display. He or she can choose multiple arts being displayed with a slider that decides how much interval there is (measured in seconds) between each art. So if the user selects 3 art pieces that he or she has rented and then slides 6 seconds on the slider. Then that means that every 6 seconds one of the 3 art pieces will get displayed.

## Shop

The shop section is a feature that has been dropped due to shortage of time.
Normally this is where the user can rent customized frames.

## Profile

Here can the user find his own "liked" art and also "rented" art.

## Info page

The info page consists of the most frequently asked questions and a contact section with all the details needed to contact Kunst In Huis
