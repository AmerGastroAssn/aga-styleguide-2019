Using AGA's new styleguide here are some of the default value variables.

There is also an example of how to add the color and text overlay to images.

HEX colors and font variables:

```css

@font-face {
    font-family: 'Gotham Regular';
    src: url('assets/fonts/gotham/GothamOffice-Regular.ttf') format("opentype");
}

@font-face {
    font-family: 'Gotham Bold';
    src: url('assets/fonts/gotham/GothamOffice-Bold.ttf') format("opentype");
}

.AvenirLTStd-Heavy {
    font-family: AvenirLTStd-Heavy;
    font-weight: normal;
    font-style: normal;
}

.AvenirLTStd-MediumOblique {
    font-family: AvenirLTStd-MediumOblique;
    font-weight: normal;
    font-style: normal;
}

.AvenirLTStd-Medium {
    font-family: AvenirLTStd-Medium;
    font-weight: normal;
    font-style: normal;
}

.AvenirLTStd-BookOblique {
    font-family: AvenirLTStd-BookOblique;
    font-weight: normal;
    font-style: normal;
}

.AvenirLTStd-Book {
    font-family: AvenirLTStd-Book;
    font-weight: normal;
    font-style: normal;
}

.AvenirLTStd-HeavyOblique {
    font-family: AvenirLTStd-HeavyOblique;
    font-weight: normal;
    font-style: normal;
}

:root {
    /* Fonts */
    --serif: 'Georgia', Cambria, serif !important;
    --sans-serif: 'Gotham Regular', AvenirLTStd-Book, 'Gotham Book', 'Avenir Next', 'Nunito', sans-serif !important;
    --sans-serif-bold: 'Gotham Bold', AvenirLTStd-Heavy, 'Gotham Book', 'Avenir Next', 'Nunito', sans-serif !important;
    --gotham: "Gotham Regular", "Gotham SSm A", "Gotham SSm B", sans-serif !important;
    --monospace: 'SF Mono', Menlo, 'Roboto Mono', 'Deja Vu Sans Mono', 'Monaco', monospace !important;

    /* Colors */
    --dark: #122033;
    --light: #fff;
    --light-gray: #FCFDFD;
    --midnight: #122033;
    --matt-blue: #202C40;
    --granite: #678598;
    --ocean: #00588a;
    --sky: #008fd5;
    --ice: #69badf;
    --water: #abe1fa;
    --water-rgb: rgb(169.0, 225.0, 251.0);
    --steel: #8fb0c5;
    --ash: #94a3ac;
    --silver: #dcddde;
    --cloud: #f2f6f8;
    --avocado: #67952e;
    --grass: #9bcb40;
    --lime: #c8da2b;
    --plum: #96157c;
    --plum-rgb: rgb(152.0, 9.0, 125.0);
    --gum: #d0167c;
    --gum-rgb: rgb(210.0, 6.0, 124.0);
    --brick: #b02a30;
    --valencia: #f58320;
    --gold: #faa61a;

    /* Link Colors */
    --link-blue: #C4E5F5;
    --link-gray: #F1F5F6;
    --link-yellow: #FFD081;

    /* Homepage Colors */
    --sec-one-blue: #C8EBFB;
    --sec-two-blue: #E3F4FC;

}

```