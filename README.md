@ -0,0 +1,781 @@
{
  "settings": {
    "name": "RSHiDes",
    "currentPage": "index.html",
    "theme": {
      "name": "mobirise4",
      "title": "Mobirise 4",
      "styling": {
        "primaryColor": "#284b24",
        "secondaryColor": "#ff3366",
        "successColor": "#F7ED4A",
        "infoColor": "#82786E",
        "warningColor": "#879A9F",
        "dangerColor": "#B1A374",
        "mainFont": "Rubik",
        "display1Font": "Rubik",
        "display1Size": 4.25,
        "display2Font": "Rubik",
        "display2Size": 3,
        "display5Font": "Rubik",
        "display5Size": "1.8",
        "display7Font": "Rubik",
        "display7Size": "1.4",
        "display4Font": "Rubik",
        "display4Size": 1,
        "isRoundedButtons": true,
        "isAnimatedOnScroll": false,
        "isScrollToTopButton": false
      },
      "additionalSetColors": [
        "#284b24",
        "#142f1c",
        "#32532e",
        "#595454"
      ]
    },
    "path": "@PROJECT_PATH@",
    "siteFonts": [
      {
        "css": "'Rubik', sans-serif",
        "name": "Rubik",
        "url": "https://fonts.googleapis.com/css?family=Rubik:300,300i,400,400i,500,500i,700,700i,900,900i"
      },
      {
        "css": "'Arimo', sans-serif",
        "name": "Arimo",
        "url": "https://fonts.googleapis.com/css?family=Arimo:400,400i,700,700i"
      },
      {
        "css": "'Asap', sans-serif",
        "name": "Asap",
        "url": "https://fonts.googleapis.com/css?family=Asap:400,400i,500,500i,600,600i,700,700i"
      }
    ],
    "versionFirst": "4.7.6",
    "uniqCompNum": 64,
    "versionPublish": "4.12.4",
    "imageResize": true,
    "screenshot": "screenshot.png",
    "cookiesAlert": {
      "customDialogSelector": false,
      "colorText": "#424a4d",
      "colorBg": "#eaeff1",
      "colorButton": "",
      "colorLink": "#424a4d",
      "underlineLink": true,
      "opacity": "99",
      "opacityOverlay": "80",
      "text": "We use cookies to give you the best experience. Read our <a href='privacy.html'>cookie policy</a>.",
      "textButton": "Agree"
    },
    "favicon": false,
    "robotsSwitcher": false,
    "sitemapSwitcher": true,
    "sitemapSwitcherAuto": "on",
    "siteUrl": "https://rshides.github.io/irshides/",
    "gdpr": false,
    "robotsText": "User-agent: *\r\nDisallow: /cgi-bin\r\n"
  },
  "pages": {
    "index.html": {
      "settings": {
        "main": true,
        "title": "Rshides",
        "meta_descr": "",
        "header_custom": "",
        "footer_custom": "",
        "html_before": ""
      },
      "components": [
        {
          "_styles": {
            ".navbar": {
              "padding": ".5rem 0",
              "background": "@menuBgColor",
              "transition": "none",
              "min-height": "77px"
            },
            ".navbar-dropdown.bg-color.transparent.opened": {
              "background": "@menuBgColor"
            },
            "a": {
              "font-style": "normal"
            },
            ".nav-item": {
              "& span": {
                "padding-right": "0.4em",
                "line-height": "0.5em",
                "vertical-align": "text-bottom",
                "position": "relative",
                "text-decoration": "none"
              },
              "& a": {
                "display": "flex",
                "align-items": "center",
                "justify-content": "center",
                "padding": "0.7rem 0 !important",
                "margin": "0rem .65rem !important"
              }
            },
            ".nav-item:focus, .nav-link:focus": {
              "outline": "none"
            },
            ".btn": {
              "padding": "0.4rem 1.5rem",
              ".mbr-iconfont": {
                "font-size": "1.6rem"
              },
              "display": "inline-flex",
              "align-items": "center"
            },
            ".menu-logo": {
              "margin-right": "auto",
              ".navbar-brand": {
                "display": "flex",
                "margin-left": "5rem",
                "padding": "0",
                "transition": "padding .2s",
                "min-height": "3.8rem",
                "align-items": "center",
                ".navbar-caption-wrap": {
                  "display": "-webkit-flex",
                  "-webkit-align-items": "center",
                  "align-items": "center",
                  "word-break": "break-word",
                  "min-width": "7rem",
                  "margin": ".3rem 0",
                  ".navbar-caption": {
                    "line-height": "1.2rem !important",
                    "padding-right": "2rem"
                  }
                },
                ".navbar-logo": {
                  "font-size": "4rem",
                  "transition": "font-size 0.25s",
                  "& img": {
                    "display": "flex"
                  },
                  ".mbr-iconfont": {
                    "transition": "font-size 0.25s"
                  }
                }
              }
            },
            ".navbar-toggleable-sm .navbar-collapse": {
              "justify-content": "flex-end",
              "-webkit-justify-content": "flex-end",
              "padding-right": "5rem",
              "width": "auto",
              ".navbar-nav": {
                "flex-wrap": "wrap",
                "-webkit-flex-wrap": "wrap",
                "padding-left": "0",
                ".nav-item": {
                  "-webkit-align-self": "center",
                  "align-self": "center"
                }
              },
              ".navbar-buttons": {
                "padding-left": "0",
                "padding-bottom": "0"
              }
            },
            ".dropdown": {
              ".dropdown-menu": {
                "background": "@menuBgColor",
                "display": "none",
                "position": "absolute",
                "min-width": "5rem",
                "padding-top": "1.4rem",
                "padding-bottom": "1.4rem",
                "text-align": "left",
                ".dropdown-item": {
                  "width": "auto",
                  "padding": "0.235em 1.5385em 0.235em 1.5385em !important",
                  "&::after": {
                    "right": "0.5rem"
                  }
                },
                ".dropdown-submenu": {
                  "margin": "0"
                }
              },
              "&.open > .dropdown-menu": {
                "display": "block"
              }
            },
            ".navbar-toggleable-sm": {
              "&.opened:after": {
                "position": "absolute",
                "width": "100vw",
                "height": "100vh",
                "content": "''",
                "background-color": "rgba(0, 0, 0, 0.1)",
                "left": "0",
                "bottom": "0",
                "transform": "translateY(100%)",
                "-webkit-transform": "translateY(100%)",
                "z-index": "1000"
              }
            },
            ".navbar.navbar-short": {
              "min-height": "60px",
              "transition": "all .2s",
              "& .navbar-toggler-right": {
                "top": "20px"
              },
              "& .navbar-logo a": {
                "font-size": "2.5rem !important",
                "line-height": "2.5rem",
                "transition": "font-size 0.25s",
                "& .mbr-iconfont": {
                  "font-size": "2.5rem !important"
                },
                "& img": {
                  "height": "3rem !important"
                }
              },
              "& .navbar-brand": {
                "min-height": "3rem"
              }
            },
            "button.navbar-toggler": {
              "width": "31px",
              "height": "18px",
              "cursor": "pointer",
              "transition": "all .2s",
              "top": "1.5rem",
              "right": "1rem",
              "&:focus": {
                "outline": "none"
              },
              ".hamburger span": {
                "position": "absolute",
                "right": "0",
                "width": "30px",
                "height": "2px",
                "border-right": "5px",
                "background-color": "@hamburgerColor",
                "&:nth-child(1)": {
                  "top": "0",
                  "transition": "all .2s"
                },
                "&:nth-child(2)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(3)": {
                  "top": "8px",
                  "transition": "all .15s"
                },
                "&:nth-child(4)": {
                  "top": "16px",
                  "transition": "all .2s"
                }
              }
            },
            "nav.opened .hamburger span": {
              "&:nth-child(1)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              },
              "&:nth-child(2)": {
                "-webkit-transform": "rotate(45deg)",
                "transform": "rotate(45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(3)": {
                "-webkit-transform": "rotate(-45deg)",
                "transform": "rotate(-45deg)",
                "transition": "all .25s"
              },
              "&:nth-child(4)": {
                "top": "8px",
                "width": "0",
                "opacity": "0",
                "right": "50%",
                "transition": "all .2s"
              }
            },
            ".collapsed": {
              "&.navbar-expand": {
                "flex-direction": "column"
              },
              ".btn": {
                "display": "flex"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (max-width: 991px)": {
              ".navbar-expand": {
                "flex-direction": "column"
              },
              "img": {
                "height": "3.8rem !important"
              },
              ".btn": {
                "display": "flex"
              },
              "button.navbar-toggler": {
                "display": "block"
              },
              ".navbar-brand": {
                "margin-left": "1rem !important"
              },
              ".navbar-toggleable-sm": {
                "flex-direction": "column",
                "-webkit-flex-direction": "column"
              },
              ".navbar-collapse": {
                "display": "none !important",
                "padding-right": "0 !important",
                "&.collapsing,&.show": {
                  "display": "block !important",
                  ".navbar-nav": {
                    "display": "block",
                    "text-align": "center",
                    ".nav-item": {
                      "clear": "both",
                      "& when (@showButtons = false)": {
                        "&:last-child": {
                          "margin-bottom": "1rem"
                        }
                      }
                    }
                  },
                  ".navbar-buttons": {
                    "text-align": "center",
                    "&:last-child": {
                      "margin-bottom": "1rem"
                    }
                  }
                }
              },
              ".dropdown": {
                ".dropdown-menu": {
                  "width": "100%",
                  "text-align": "center",
                  "position": "relative",
                  "opacity": "0",
                  "display": "block",
                  "height": "0",
                  "visibility": "hidden",
                  "padding": "0",
                  "transition-duration": ".5s",
                  "transition-property": "opacity,padding,height"
                },
                "&.open > .dropdown-menu": {
                  "position": "relative",
                  "opacity": "1",
                  "height": "auto",
                  "padding": "1.4rem 0",
                  "visibility": "visible"
                },
                ".dropdown-submenu": {
                  "left": "0",
                  "text-align": "center",
                  "width": "100%"
                },
                ".dropdown-toggle[data-toggle=\"dropdown-submenu\"]::after": {
                  "margin-top": "0",
                  "position": "inherit",
                  "right": "0",
                  "top": "50%",
                  "display": "inline-block",
                  "width": "0",
                  "height": "0",
                  "margin-left": ".3em",
                  "vertical-align": "middle",
                  "content": "\"\"",
                  "border-top": ".30em solid",
                  "border-right": ".30em solid transparent",
                  "border-left": ".30em solid transparent"
                }
              }
            },
            "@media (min-width: 767px)": {
              ".menu-logo": {
                "flex-shrink": "0"
              }
            },
            ".navbar-collapse": {
              "flex-basis": "auto"
            },
            ".nav-link:hover, .dropdown-item:hover": {
              "color": "@itemsHoverColor !important"
            }
          },
          "_name": "menu1",
          "_customHTML": "<section class=\"menu\" group=\"Menu\" plugins=\"DropDown, TouchSwipe\" always-top global once=\"menu\" not-draggable position-absolute>\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Show Logo\" name=\"showLogo\" checked>\n        <input type=\"range\" title=\"Logo Size\" inline name=\"logoSize\" min=\"3.8\" max=\"8\" step=\"0.1\" value=\"3.8\" condition=\"showLogo\">\n        <input type=\"checkbox\" title=\"Show Brand Name\" name=\"showBrand\">\n        <input type=\"checkbox\" title=\"Show Menu Items\" name=\"showItems\">\n        <input type=\"color\" title=\"Items Hover Color\" name=\"itemsHoverColor\" value=\"#142f1c\" condition=\"showItems\">\n        <input type=\"checkbox\" title=\"Show Button(s)\" name=\"showButtons\">\n        <input type=\"checkbox\" title=\"Sticky\" name=\"sticky\" checked>\n        <input type=\"checkbox\" title=\"Collapsed\" name=\"collapsed\">\n        <input type=\"checkbox\" title=\"Transparent\" name=\"transparent\" checked>\n        <input type=\"color\" title=\"Hamburger Color\" name=\"hamburgerColor\" value=\"#142f1c\">\n        <input type=\"color\" title=\"Background Color\" name=\"menuBgColor\" value=\"#ffffff\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <nav class=\"navbar navbar-expand beta-menu navbar-dropdown align-items-center\" mbr-class=\"{'navbar-fixed-top': sticky,\n        'navbar-toggleable-sm': !collapsed,\n        'collapsed': collapsed,\n        'bg-color transparent': transparent}\">\n        <button class=\"navbar-toggler navbar-toggler-right\" type=\"button\" data-toggle=\"collapse\" data-target=\"#navbarSupportedContent\" aria-controls=\"navbarSupportedContent\" aria-expanded=\"false\" aria-label=\"Toggle navigation\">\n            <div class=\"hamburger\">\n                <span></span>\n                <span></span>\n                <span></span>\n                <span></span>\n            </div>\n        </button>\n        <div class=\"menu-logo\">\n            <div class=\"navbar-brand\">\n                <span mbr-if=\"showLogo\" class=\"navbar-logo\">\n                    <a href=\"https://mobirise.com\">\n                         <img src=\"@PROJECT_PATH@/assets/images/rshid-copy-10-546x157.png\" alt=\"Mobirise\" mbr-style=\"{'height': logoSize + 'rem'}\" title>\n                    </a>\n                </span>\n                <span mbr-if=\"showBrand\" mbr-buttons mbr-theme-style=\"display-4\" class=\"navbar-caption-wrap\" data-toolbar=\"-mbrBtnMove,-mbrBtnAdd,-mbrBtnRemove\"><a class=\"navbar-caption text-white\" data-app-selector=\".navbar-caption\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                        r\n                    </a></span>\n            </div>\n        </div>\n        <div class=\"collapse navbar-collapse\" id=\"navbarSupportedContent\">\n            <ul mbr-if=\"showItems\" mbr-menu class=\"navbar-nav nav-dropdown\" mbr-theme-style=\"display-7\" mbr-class=\"{'nav-right': !showButtons,'navbar-nav-top-padding': isPublish && !showBrand && !showLogo}\"><li class=\"nav-item\">\n                    <a class=\"nav-link link text-primary\" href=\"index.html\" data-app-selector=\".nav-link,.dropdown-item\" data-app-placeholder=\"Type Text\"></a>\n                </li></ul>\n            <div mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-7\" class=\"navbar-buttons mbr-section-btn\"><a class=\"btn btn-sm btn-primary\" href=\"https://mobirise.com\" data-app-placeholder=\"Type Text\">\n                    <span class=\"mbri-save mbr-iconfont mbr-iconfont-btn \" data-app-selector=\".mbr-iconfont-btn\"></span>\n                    Try It Now!\n                </a></div>\n        </div>\n    </nav>\n</section>",
          "_cid": "qTkzRZLJNu",
          "_anchor": "menu1-0",
          "_protectedParams": [],
          "_global": true,
          "_once": "menu",
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "P": {
              "color": "#767676"
            },
            "H1": {
              "text-align": "center",
              "color": "#635a51"
            },
            "H3": {
              "text-align": "center",
              "color": "#595454"
            },
            ".mbr-text, .mbr-section-btn": {
              "text-align": "center",
              "color": "#232323"
            }
          },
          "_name": "header16",
          "_customHTML": "<section class=\"header1\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/animated-6.gif\" parallax selected>\n            <input type=\"color\" title=\"Background Color\" value=\"#efefef\">\n            <input type=\"video\" title=\"Background Video\" value=\"https://youtu.be/il_tGrMh8Ts\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#efefef\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"row justify-content-md-center\">\n            <div class=\"col-md-10 align-center\">\n                <h1 class=\"mbr-section-title mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showTitle\"><span style=\"font-weight: normal;\">هوية تعلق بالذاكرة وتعزز مكانتك</span></h1>\n                <h3 class=\"mbr-section-subtitle mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\"></h3>\n                <p class=\"mbr-text pb-3 mbr-fonts-style\" mbr-theme-style=\"display-7\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\">&nbsp; نحن وكالة رشيد للدعاية والإعلان نطورالأفكارونحولها لحقيقة من أجل رؤية جديدة في عالم الهوية التجارية</p>\n                <div mbr-buttons mbr-theme-style=\"display-4\" class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\"><a class=\"btn btn-md btn-black-outline\" href=\"https://mobirise.co\" data-app-placeholder=\"Type Text\">LEARN MORE</a>\n                </div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "s5SMyzjel9",
          "_anchor": "header16-m",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value",
              "& when (@gradientBg)": {
                "background": "linear-gradient(45deg, @bg-value, @color2)"
              }
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@reverseContent)": {
              ".media-container-row": {
                "flex-direction": "row-reverse",
                "-webkit-flex-direction": "row-reverse"
              }
            },
            ".mbr-figure": {
              "@media (min-width: 992px)": {
                "padding-right": "4rem",
                "& when (@reverseContent)": {
                  "padding-right": "0",
                  "padding-left": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                "padding-bottom": "3rem"
              }
            },
            ".mbr-text": {
              "@media (max-width: 767px)": {
                "text-align": "center"
              }
            },
            "H1": {
              "color": "#142f1c",
              "text-align": "right"
            },
            ".mbr-text, .mbr-section-btn": {
              "color": "#284b24",
              "text-align": "right"
            }
          },
          "_name": "header3",
          "_customHTML": "<section class=\"header3\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n    \n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n        <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"10\" max=\"200\" step=\"5\" value=\"170\">\n        <input type=\"checkbox\" title=\"Media On Left/Right\" name=\"reverseContent\" checked>\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n\n        <input type=\"checkbox\" title=\"Gradient\" name=\"gradientBg\" condition=\"bg.type == 'color'\" checked>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#ffffff\" condition=\"gradientBg && bg.type == 'color'\">\n        \n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.8\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"mbr-figure\" mbr-style=\"{'width': mediaSize + '%'}\">\n                <img src=\"@PROJECT_PATH@/assets/images/animated-4.gif\" alt=\"Mobirise\" title>\n            </div>\n\n            <div class=\"media-content\">\n                <h1 class=\"mbr-section-title mbr-white pb-3 mbr-fonts-style\" mbr-if=\"showTitle\" mbr-theme-style=\"display-5\">بناء الهوية -</h1>\n                <h3 class=\"mbr-section-subtitle align-left mbr-white mbr-light pb-3 mbr-fonts-style\" mbr-if=\"showSubTitle\" mbr-theme-style=\"display-2\">\n                    Beautiful mobile websites\n                </h3>\n                <div class=\"mbr-section-text mbr-white pb-3 \">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\" mbr-theme-style=\"display-5\">\n                        نعمل على بناء الهوية بتصميم الشعار وفرز الألوان وتصميم المطبوعات الرئيسية (الكروت الشخصية- الملف-الورق الرسمي-الأظرف-الأكياس الورقية-ورق الملاحظات-بانر إعلاني) هدفنا صنع هوية مواكبة وتعبر عن مجال عملك</p>\n                </div>\n                <div class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-primary-outline\" href=\"index.html#form1-1q\" data-app-placeholder=\"Type Text\">تقدم بالطلب</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "s5YPsJQ7y3",
          "_anchor": "header3-1n",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value",
              "& when (@gradientBg)": {
                "background": "linear-gradient(45deg, @bg-value, @color2)"
              }
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@reverseContent)": {
              ".media-container-row": {
                "flex-direction": "row-reverse",
                "-webkit-flex-direction": "row-reverse"
              }
            },
            ".mbr-figure": {
              "@media (min-width: 992px)": {
                "padding-right": "4rem",
                "& when (@reverseContent)": {
                  "padding-right": "0",
                  "padding-left": "4rem"
                }
              },
              "@media (max-width: 991px)": {
                "padding-bottom": "3rem"
              }
            },
            ".mbr-text": {
              "@media (max-width: 767px)": {
                "text-align": "center"
              }
            },
            "H1": {
              "color": "#142f1c",
              "text-align": "right"
            },
            ".mbr-text, .mbr-section-btn": {
              "color": "#32532e",
              "text-align": "right"
            }
          },
          "_name": "header3",
          "_customHTML": "<section class=\"header3\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"4\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n    \n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\">\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n        <input type=\"range\" inline title=\"Media Size\" name=\"mediaSize\" min=\"10\" max=\"200\" step=\"5\" value=\"185\">\n        <input type=\"checkbox\" title=\"Media On Left/Right\" name=\"reverseContent\" checked>\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"https://www.youtube.com/watch?v=36YgDDJ7XSc\">\n        </fieldset>\n\n        <input type=\"checkbox\" title=\"Gradient\" name=\"gradientBg\" condition=\"bg.type == 'color'\" checked>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#ffffff\" condition=\"gradientBg && bg.type == 'color'\">\n        \n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.8\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"mbr-figure\" mbr-style=\"{'width': mediaSize + '%'}\">\n                <img src=\"@PROJECT_PATH@/assets/images/animated-5.gif\" alt=\"Mobirise\" title>\n            </div>\n\n            <div class=\"media-content\">\n                <h1 class=\"mbr-section-title mbr-white pb-3 mbr-fonts-style\" mbr-if=\"showTitle\" mbr-theme-style=\"display-5\">عمل &nbsp;مخطوطة -</h1>\n                <h3 class=\"mbr-section-subtitle align-left mbr-white mbr-light pb-3 mbr-fonts-style\" mbr-if=\"showSubTitle\" mbr-theme-style=\"display-2\">\n                    Beautiful mobile websites\n                </h3>\n                <div class=\"mbr-section-text mbr-white pb-3 \">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-if=\"showText\" data-app-selector=\".mbr-text, .mbr-section-btn\" mbr-theme-style=\"display-5\">نعمل على صنع مخطوطة بما يتوافق مع طبيعة اعلانك التجاري وعلامتك التجارية</p>\n                </div>\n                <div class=\"mbr-section-btn\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-primary-outline\" href=\"index.html#form1-1q\" data-app-placeholder=\"Type Text\">تقدم بالطلب</a></div>\n            </div>\n        </div>\n    </div>\n\n</section>",
          "_cid": "s5ZmtwUh9c",
          "_anchor": "header3-1o",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".title": {
              "margin-bottom": "2rem"
            },
            ".mbr-section-subtitle": {
              "color": "#635a51"
            },
            "a:not([href]):not([tabindex])": {
              "color": "#fff",
              "border-radius": "3px"
            },
            "a.btn-white:not([href]):not([tabindex])": {
              "color": "#333"
            },
            "textarea.form-control": {
              "min-height": "188px"
            },
            "LABEL": {
              "text-align": "right",
              "color": "#284b24"
            },
            "H2": {
              "color": "#284b24"
            }
          },
          "_name": "form1",
          "_customHTML": "<section class=\"mbr-section form1\" group=\"Forms\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" value=\"6\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" value=\"6\">\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#c1c1c1\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container\">\n        <div class=\"row justify-content-center\">\n            <div class=\"title col-12 col-lg-8\">\n                <h2 mbr-if=\"showTitle\" class=\"mbr-section-title align-center pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\">\n                    تواصل معنا</h2>\n                <h3 mbr-if=\"showSubtitle\" class=\"mbr-section-subtitle align-center mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" data-app-selector=\".mbr-section-subtitle\">\n                    تواصل معنا</h3>\n            </div>\n        </div>\n    </div>\n    <div class=\"container\">\n        <div class=\"row justify-content-center\">\n            <div mbr-form class=\"media-container-column col-lg-8\">\n                <!---Formbuilder Form--->\n                <form action=\"i@rshides.com\" name=\"Mobirise Form\" method=\"POST\" class=\"mbr-form form-with-styler\">\n                    <div class=\"row\">\n                        <div hidden=\"hidden\" data-form-alert class=\"alert alert-success col-12\">شكرا على ثقتكم ونسعد بخدمتكم</div>\n                        <div hidden=\"hidden\" data-form-alert-danger class=\"alert alert-danger col-12\">\n                        </div>\n                    </div>\n                    <div class=\"dragArea row\">\n                        <div class=\"col-md-4  form-group\" data-for=\"name\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"name\" class=\"form-control-label mbr-fonts-style\"><b>الاسم</b></label>\n                            <input type=\"text\" name=\"name\" data-form-field=\"Name\" mbr-theme-style=\"display-7\" required=\"required\" class=\"form-control\">\n                        </div>\n                        <div class=\"col-md-4  form-group\" data-for=\"email\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"email\" class=\"form-control-label mbr-fonts-style\"><b>البريد الإلكتروني</b></label>\n                            <input type=\"email\" name=\"email\" data-form-field=\"Email\" mbr-theme-style=\"display-7\" required=\"required\" class=\"form-control\">\n                        </div>\n                        <div data-for=\"phone\" class=\"col-md-4  form-group\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"phone\" class=\"form-control-label mbr-fonts-style\"><b>رقم الجوال</b></label>\n                            <input type=\"tel\" name=\"phone\" data-form-field=\"Phone\" mbr-theme-style=\"display-7\" class=\"form-control\">\n                        </div>\n                        <div data-for=\"message\" class=\"col-md-12 form-group\">\n                            <label mbr-text mbr-theme-style=\"display-7\" for=\"message\" class=\"form-control-label mbr-fonts-style\"><b>الخدمه المطلوبة</b></label>\n                            <textarea name=\"message\" data-form-field=\"Message\" mbr-theme-style=\"display-7\" class=\"form-control\"></textarea>\n                        </div>\n                        <div class=\"col-md-12 input-group-btn align-center\" mbr-buttons=\"true\" mbr-theme-style=\"display-4\" data-toolbar=\"-mbrBtnMove,-mbrBtnLink,-mbrBtnAdd\"><a type=\"submit\" class=\"btn btn-form btn-primary\" data-app-placeholder=\"Type Text\">ارسال</a></div>\n                    </div>\n                </form><!---Formbuilder Form--->\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "s62A8omuEF",
          "_anchor": "form1-1q",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "alias": false,
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            ".media-wrap": {
              "@media (max-width: 767px)": {
                "margin-bottom": "1rem",
                "text-align": "center"
              },
              ".mbr-iconfont-logo": {
                "font-size": "7rem",
                "color": "#f36"
              },
              "img": {
                "height": "6rem"
              }
            },
            ".mbr-text": {
              "color": "#767676"
            },
            ".footer-lower": {
              ".copyright": {
                "@media (max-width: 767px)": {
                  "margin-bottom": "1rem",
                  "text-align": "center"
                }
              },
              "hr": {
                "margin": "1rem 0",
                "border-color": "#000",
                "opacity": ".05"
              },
              ".social-list": {
                "padding-left": "0",
                "margin-bottom": "0",
                "list-style": "none",
                "display": "flex",
                "-webkit-flex-wrap": "wrap",
                "flex-wrap": "wrap",
                "-webkit-justify-content": "flex-end",
                "justify-content": "flex-end",
                ".mbr-iconfont-social": {
                  "font-size": "1.3rem",
                  "color": "#232323"
                },
                ".soc-item": {
                  "margin": "0 .5rem"
                },
                "a": {
                  "margin": "0",
                  "opacity": ".5",
                  "-webkit-transition": ".2s linear",
                  "transition": ".2s linear",
                  "&:hover": {
                    "opacity": "1"
                  }
                },
                "@media (max-width: 767px)": {
                  "-webkit-justify-content": "center",
                  "justify-content": "center"
                }
              }
            },
            ".links": {
              "color": "#284b24"
            },
            ".links P": {
              "text-align": "right"
            }
          },
          "_name": "footer5",
          "_customHTML": "<section group=\"footer5\" mbr-class=\"{'mbr-reveal': reveal, 'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"3\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"3\">\n        <input type=\"checkbox\" title=\"Show Copyright\" name=\"showCopyright\" checked>\n        <select title=\"Icons\" name=\"iconsCount\">\n            <option value=\"0\">0</option>\n            <option value=\"1\">1</option>\n            <option value=\"2\" selected>2</option>\n            <option value=\"3\">3</option>\n            <option value=\"4\">4</option>\n            <option value=\"5\">5</option>\n            <option value=\"6\">6</option>\n        </select>\n        <input type=\"checkbox\" title=\"Reveal effect\" name=\"reveal\">\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background5.jpg\">\n            <input type=\"color\" title=\"Background Color\" value=\"#ffffff\" selected>\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\" checked>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#efefef\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.9\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type !== 'color'\" opacity=\"{{overlayOpacity}}\" bg-color=\"{{overlayColor}}\"></div>\n\n    <div class=\"container\">\n        <div class=\"media-container-row\">\n            <div class=\"col-md-3\">\n                <div class=\"media-wrap\">\n                    <a href=\"https://mobirise.co/\">\n                       <img src=\"@PROJECT_PATH@/assets/images/rshid-copy-10-192x108.png\" alt=\"Mobirise\" title>\n                    </a>\n                </div>\n            </div>\n            <div class=\"col-md-9\">\n                <p class=\"mbr-text align-right links mbr-fonts-style\" mbr-theme-style=\"display-7\" data-app-selector=\".links\"></p>\n            </div>\n        </div>\n        <div class=\"footer-lower\" mbr-if=\"showCopyright\">\n            <div class=\"media-container-row\">\n                <div class=\"col-md-12\">\n                    <hr>\n                </div>\n            </div>\n            <div class=\"media-container-row mbr-white\">\n                <div class=\"col-md-6 copyright\">\n                    <p class=\"mbr-text mbr-fonts-style\" mbr-theme-style=\"display-4\" data-app-selector=\".copyright > p\">\n                        © 2020 RSHiDes Adversting Agency - All Rights Reserved\n                    </p>\n                </div>\n                <div class=\"col-md-6\">\n                    <div class=\"social-list align-right\" mbr-if=\"iconsCount > 0\">\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>0\">\n                            <a href=\"https://instagram.com/rshid_es?igshid=1nivt5cox9s14\" target=\"_blank\">\n                                <span mbr-icon class=\"mbr-iconfont mbr-iconfont-social socicon-instagram socicon\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>1\">\n                            <a href=\"https://twitter.com/rshid_des?s=21\" target=\"_blank\">\n                                <span mbr-icon class=\"mbr-iconfont mbr-iconfont-social socicon-twitter socicon\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>2\">\n                            <a href=\"https://www.youtube.com/c/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-youtube socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>3\">\n                            <a href=\"https://instagram.com/mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-instagram socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>4\">\n                            <a href=\"https://plus.google.com/u/0/+Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-googleplus socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                        <div class=\"soc-item\" mbr-if=\"iconsCount>5\">\n                            <a href=\"https://www.behance.net/Mobirise\" target=\"_blank\">\n                                <span mbr-icon class=\"socicon-behance socicon mbr-iconfont mbr-iconfont-social\"></span>\n                            </a>\n                        </div>\n                    </div>\n                </div>\n            </div>\n        </div>\n    </div>\n</section>",
          "_cid": "s62GJLSbq9",
          "_anchor": "footer5-1r",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    }
  }
}
