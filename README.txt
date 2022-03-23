# Learning of Sass

Front end dedicated to learn the principal fonctionnalities of Sass (mixins, maps, 7-1, ...).
Colors, text-sixe, text-content and margin are updaptable and dedicated to test (sorry for colors). 

Code composition : 
    -index.html : contains html Code.
    -images folder : contains the downloaded images.
    -package.json : In this case, used only for charging the Sass script.
    -sass folders : -base folder : -base.scss : contains rules for basic parameters
                                    -typography.scss : Actually empty (created for the openclassrooms course)
                    -components folder : Actually empty (created for the openclassrooms course)
                    -layout folder : -footer.scss : contains all rules for the footer
                                    - header.scss : contains all rules for the header
                    -pages folder : -section-work.scss : contains all rules for the first section of the body
                                    - section-english.scss : contains all rules for the second section of the body
                    -themes folder : Actually empty (created for the openclassrooms course)
                    -utils folder : - extensions.scss : Actually empty (created for the openclassrooms course)
                                    - functions.scss : contains all functions of this website
                                    - mixins.scss : contains all mixins of this website
                                    - variables.scss : contains all variables of this website
                    -vendors folder: Actually empty (created for the openclassrooms course)
                    -main.scss : contains all links to import in css file
    -css folders : - style.css : All the code in css language
                    - style.css.map : Contains the map to find style.css
                    - prefixed folders : - style.css : contains a version of the css code with autoprefixer to translate it to the different navigators.