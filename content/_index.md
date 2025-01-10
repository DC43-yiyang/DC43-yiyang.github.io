---
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: "Compbio Wizard Group @ MD Anderson"  
      subtitle: ""
      text: |
        <script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@latest/dist/js/splide.min.js"></script>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@latest/dist/css/splide.min.css">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fancyapps/ui/dist/fancybox.css" />
        <script src="https://cdn.jsdelivr.net/npm/@fancyapps/ui/dist/fancybox.umd.js"></script>

        <style>
            img{
                cursor: pointer;
            }
            .slide-container {
                position: relative;
                display: inline-block;
            }
            .project-link {
                position: absolute;
                bottom: 10px;
                right: 10px;
                background-color: rgba(30, 115, 190, 0.9);
                color: white;
                padding: 5px 15px;
                border-radius: 4px;
                text-decoration: none;
                font-size: 14px;
                transition: all 0.3s ease;
            }
            .project-link:hover {
                background-color: rgba(25, 95, 160, 1);
                color: white;
                text-decoration: none;
            }
            .splide figcaption {
                margin-bottom: 20px;
                padding-bottom: 10px;
                position: relative;
                z-index: 2;
            }
            .splide__pagination {
                bottom: -5px !important;
            }
        </style>

        <div class="row">
        <div class="col-12 col-md-6">
        <!-- Introduction -->
        The Compbio Wizard Group focuses on developing innovative computational methods 
        for solving complex biological problems. Our research spans bioinformatics, 
        machine learning, and systems biology.
        </div>

        <div class="col-12 col-md-6">
        <div class="splide">
          <div class="splide__track">
            <ul class="splide__list">
              <li class="splide__slide">
                <div class="splide__slide__container">
                  <center>
                    <div class="slide-container">
                      <div data-src="media/coders.jpg" data-fancybox="gallery" data-caption="Group Meeting">
                        <img style="height: 375px" src="media/coders.jpg">
                      </div>
                      <a href="https://dc43-yiyang.github.io/people/" class="project-link" onclick="event.stopPropagation()">
                        Meet the CompBio Wizards
                      </a>
                    </div>
                    <figcaption>CompBio Wizards Meeting</figcaption>
                  </center>
                </div>
              </li>
              <li class="splide__slide">
                <div class="splide__slide__container">
                  <center>
                    <div class="slide-container">
                      <div data-src="media/contact.jpg" data-fancybox="gallery" data-caption="Research Projects">
                        <img style="height: 375px" src="media/contact.jpg">
                      </div>
                      <a href="https://dc43-yiyang.github.io/project/" class="project-link" onclick="event.stopPropagation()">
                        See Our Exciting Research
                      </a>
                    </div>
                    <figcaption>Research Projects</figcaption>
                  </center>
                </div>
              </li>
              <li class="splide__slide">
                <div class="splide__slide__container">
                  <center>
                    <div class="slide-container">
                      <div data-src="media/coders.jpg" data-fancybox="gallery" data-caption="Software">
                        <img style="height: 375px" src="media/coders.jpg">
                      </div>
                      <a href="https://dc43-yiyang.github.io/software/" class="project-link" onclick="event.stopPropagation()">
                        See Our Exciting Software
                      </a>
                    </div>
                    <figcaption>Research Software</figcaption>
                  </center>
                </div>
              </li>
              <li class="splide__slide">
                <div class="splide__slide__container">
                  <center>
                    <div class="slide-container">
                      <div data-src="media/contact.jpg" data-fancybox="gallery" data-caption="Contact">
                        <img style="height: 375px" src="media/contact.jpg">
                      </div>
                      <a href="https://dc43-yiyang.github.io/contact/" class="project-link" onclick="event.stopPropagation()">
                        Address
                      </a>
                    </div>
                    <figcaption>We Are Hiring!</figcaption>
                  </center>
                </div>
              </li>
            </ul>
          </div>
        </div>
        </div>
        </div>

        <script>
        new Splide('.splide', {
          type: 'loop',
          autoplay: true,
          trimSpace: true,
          focus: 'center',
        }).mount();
        </script>

        <script>
        Fancybox.bind('[data-fancybox="gallery"]', {
          Thumbs: false,
          Toolbar: false,
          closeButton: "top",
        });
        </script>

    design:
      # Choose how many columns the section has. Valid values: 1 or 2.
      columns: '1'
      background:
        # image: 'background.jpg'  
        # image_size: cover
        # image_position: center
        # image_parallax: true
        # text_color_light: true
      spacing:
        padding: ["40px", "0", "30px", "0"]
    
    advanced:
      css_style:
      css_class:
---