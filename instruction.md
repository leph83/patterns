# DESCRIPTION

Everyt Theme has its own CSS File. The Default File is the style.css File.
By Adding "css" : "themenName", to your json you change the css File.

Every Theme has a settings scss File with adjusted Variables. 
And in the css Folder you find the themeName.scss File with loaded Setting to render the themeName.css File.


SECTIONS:
Default:
The Default Section has a Section Title and Subtitle. It also has an optional Section Background Image.
It Contains the block-text-up Blocks.
It is highly adjustable and usable for News, Events, Default Text and Galleries. 
If only section title and subtitle used the default section can also be used as an inset section.
When you want a slider with inset title and subtitle, proceed to inset Section.

Inset:
The Inset Section contains inset blocks. Used for Sliders, Galleries where the Title is inside the Image etc. Short: Where Content is above Background Image. 

Reverse:
The Reversed Section contains Blocks with the image after the content. Otherwise it's exactly the same as the default section.


Nested:
There are no finished nested sections. You build them by yourself. 



Block Types:
Text Top:
Image, Content


Text Bottom:
Content, Image

Inset:
Image as Background image
Content


title first:
Title
Image
Content











# JSON SETTINGS


GLOBAL SETTINGS
"css" : "style",
"show-comments" : false,



GLOBAL TEXT
"more" : "mehr"
"all-rights" : "Alle rechte vorbehalten",
"date": "24.12.2015",



CONTACT
"show-company" : true,
"company" : "Company",
"show-address" : true,
"street" : "Streetname",
"street-nr" : "42",
"show-city" : true,
"zip" : "0815",
"city" : "Basin City",
"show-country" : true,
"country" : "Zimbabwe",
"show-phone" : true,
"phone" : "0815 300 600",
"show-fax" : true,
"fax" : "0815 300 600-15",
"show-mail" : true,
"mail" : "office@office.com",
"footer-contact-title" : "Kontakt",



OPENING TIMES
"opening" : true,


NAVIGATION
"nav-item" : "navigation",
"nav-items" : [
    {}
],

"block-nav" : true,



FOOTER
"footer-1" : true,
"footer-2" : true,
"footer-3" : true,
"footer-4" : true,



DEFAULT SECTION SETTINGS
"section-tag" : "div",
"section-modifier" : "",
"show-section-image" : false,
"section-image" : "../../../../img/testimages/werkzeuge.jpg",
"show-section-overlay" : false,

"show-section-header" : true,
    "section-header-tag" : "div",
    "section-title-tag" : "div",
    "section-subtitle-tag" : "div",
    "section-title" : "Section Title",
    "show-subtitle" : true,
    "section-subtitle" : "Section Subtitle",

"show-section-items" : true,
    "section-grid" : "",
    "section-grid-item" : "",
    "section-items" : [
        {}
    ],

"show-section-button" : false



DEFAULT BLOCK SETTINGS

    "block-tag" : "div",
    "block-modifier" : "default",
    "show-block-overlay" : false,
    "show-block-link" : true,
        "show-lightbox" : false,
    "block-grid" : "",
        "block-grid-image" : "one-third",
        "block-grid-content" : "two-thirds",
    "show-block-image" : true,
        "block-image" : "http://placehold.it/1980x1280",
    "show-block-date" : false,
    "show-block-header" : true,
        "block-header-tag" : "div",
        "block-title-tag" : "div",
            "block-title" : "Block Title dolor sit (37 characters)",
        "show-block-subtitle" : false,
            "block-subtitle-tag" : "div",
            "block-subtitle" : "Block Sub Title lor sit amet, consectetur adipiscing elit. (72 characters)",
    "show-block-excerpt" : true,
        "block-excerpt" : "Block excerpt dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.",
    "show-block-more" : false,