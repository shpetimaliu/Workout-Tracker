
[![ALIU|Shpetim](https://bdesign-agency.com/wp-content/uploads/2023/04/dTxpPi9lDf.thumb_-1.png)](https://codepen.io/shpetimaliu)

🇺🇸


# Workout Tracker

This script is a workout tracker application that allows users to record and track their running and cycling workouts. It uses JavaScript and HTML for the user interface and functionality. The script utilizes object-oriented programming(OOP) principles to create workout objects and perform calculations based on user input.

## Usage

To use the workout tracker, follow these steps:

1. Open the HTML file containing the script in a web browser.
2. Allow the application to access your current location when prompted. This is necessary for displaying the map.
3. Fill out the workout form by selecting the workout type (running or cycling), entering the distance and duration, and optionally entering additional details such as cadence or elevation gain.
4. Submit the form to add the workout to the tracker.
5. The workout will be displayed on the map as a marker and in the workout list.
6. You can click on a workout in the list to view its location on the map.
7. To reset the tracker and clear all workouts, use the "Reset" functionality.

## Script Overview

The script consists of the following components:

1. **Workout Class**: Represents a workout object with properties such as date, ID, coordinates, distance, duration, and more. It also includes methods for calculating additional metrics and setting the workout description.

2. **Running Class**: Extends the Workout class and adds specific properties and methods for running workouts, such as cadence and pace calculation.

3. **Cycling Class**: Extends the Workout class and adds specific properties and methods for cycling workouts, such as elevation gain and speed calculation.

4. **App Class**: Manages the application's functionality, including loading the map, handling form submissions, rendering workouts on the map and workout list, and managing local storage.

5. **HTML and CSS**: The HTML file contains the necessary structure for the application, including the workout form, workout list, and map container. CSS styles are applied to create a visually appealing interface.

## Dependencies

The script relies on the following dependencies:

- Leaflet: A JavaScript library for interactive maps.
- [Leaflet CSS](https://leafletjs.com/) for styling the map.
- Font Awesome CSS for icons used in the application.

Make sure to include these dependencies in your project for the script to work correctly.

## Notes

- The script utilizes the Geolocation API to retrieve the user's current position for displaying the map. Make sure to allow location access when prompted by the browser.
- The script uses local storage to store and retrieve the workouts. This allows the data to persist even when the page is reloaded or closed. Workouts are stored as JSON objects in the local storage.
- The script includes basic form validation to ensure that the input values are valid and positive.

Feel free to modify the script to suit your specific needs or enhance its functionality.


🇦🇱

# Gjurmuesi i stërvitjeve

Ky skript është një aplikacion për vëzhgimin e ushtrimeve që lejon përdoruesit të regjistrojnë dhe vëzhgojnë ushtrimet e tyre të vrapimit dhe ecjes me biçikletë. Për interfejsin dhe funksionalitetin e tij përdoret JavaScript dhe HTML. Skripti përdor parimet e programimit objekt-orientuar(OOP) për të krijuar objekte ushtrimi dhe për të kryer llogaritjet bazuar në hyrjet e përdoruesit.

## Përdorimi

Për të përdorur vëzhguesin e ushtrimeve, ndiqni këto hapa:

1. Hapni skedarin HTML që përmban skriptën në një shfletues web.
2. Lejoni aplikacionin të qasë vendndodhjen tuaj të tanishme kur t'ju kërkohet. Kjo është e nevojshme për t'i shfaqur hartën.
3. Plotësoni formularin e ushtrimit duke zgjedhur llojin e ushtrimit (jogging ose ecje me biçikletë), duke vendosur distancën dhe kohën, dhe opsionalisht duke shtuar detaje shtesë si kadencë ose fitim në lartësi.
4. Dorëzoni formularin për të shtuar ushtrimin në vëzhgues.
5. Ushtrimi do të shfaqet në hartë si një shënues dhe në listën e ushtrimeve.
6. Mund të klikoni mbi një ushtrim në listë për të parë vendndodhjen e tij në hartë.
7. Për të rivendosur vëzhguesin dhe të fshini të gjitha ushtrimet, përdorni funksionalitetin "Rivendos".

## Përmbledhja e Skriptit

Skripti përbëhet nga komponentët e mëposhtëm:

1. **Klasa e Ushtrimit**: Paraqet një objekt ushtrimi me pronësi si data, ID, koordinata, distancë, kohë, dhe më shumë. Ajo gjithashtu përfshin metoda për llogaritjen e metrikave shtesë dhe për të vendosur përshkrimin e ushtrimit.

2. **Klasa e Joggingut**: Zgjeron klasën e Ushtrimit dhe shton pronësi dhe metoda specifike për ushtrimet e joggingut, si llogaritja e kadencës dhe ritmit.

3. **Klasa e Ecjes me Biçikletë**: Zgjeron klasën e Ushtrimit dhe shton pronësi dhe metoda specifike për ushtrimet e ecjes me biçikletë, si llogaritja e fitimit në lartësi dhe

 shpejtësisë.

4. **Klasa e Aplikacionit**: Menaxhon funksionalitetin e aplikacionit, duke përfshirë ngarkimin e hartës, trajtimin e dorëzimeve të formularit, shfaqjen e ushtrimeve në hartë dhe listën e ushtrimeve, dhe menaxhimin e ruajtjes vendore.

5. **HTML dhe CSS**: Skedari HTML përmban strukturën e nevojshme për aplikacionin, duke përfshirë formularin e ushtrimeve, listën e ushtrimeve dhe kontejnerin e hartës. Stilet CSS zbatohen për të krijuar një ndërfaqe tërheqëse vizuale.

## Varetësit

Skripti varet nga varetësit e mëposhtëm:

- Leaflet: Një bibliotekë JavaScript për harta interaktive.
- [Leaflet CSS](https://leafletjs.com/) për stilizimin e hartës.
- Font Awesome CSS për ikonat që përdoren në aplikacion.

Sigurohuni që të përfshini këto varetësa në projektin tuaj për të punuar saktë.

## Shënime

- Skripti përdor API-në e Vendndodhjes për të marrë pozicionin aktual të përdoruesit për shfaqjen e hartës. Sigurohuni që të lejoni qasjen në vendndodhjen tuaj kur t'ju kërkohet nga shfletuesi.
- Skripti përdor ruajtjen vendore për të ruajtur dhe marrë ushtrimet. Kjo lejon që të dhënat të vazhdojnë të ekzistojnë edhe kur faqja ringarkohet ose mbyllet. Ushtrimet ruhen si objekte JSON në ruajtjen vendore.
- Skripti përfshin validim të thjeshtë të formularit për të siguruar që vlerat e hyrjes janë të vlefshme dhe pozitive.

Ju lutemi, ndryshoni skriptën sipas nevojave tuaja specifike ose përforcimt të saj funksional.
