<template>
  <div>
    <base-header type="dark opacity-8" class="pb-6 pb-8 pt-5 pt-md-8">
      <!-- Card stats -->
      <div class="row">
        <div class="container-fluid d-flex align-items-center">
          <div class="row">
            <div class="col-12">
              <h2 class="display-2 text-white">Gavin's CV</h2>
            </div>
          </div>
        </div>
      </div>
    </base-header>

    <div class="container-fluid mt--7">
      <div class="row">
        <div class="col">
          <div class="card shadow">
            <div class="card-header bg-transparent">
              <h1 class="mb-0">Gavin Wu</h1>
              <span>
                <h2>
                  gavin.wu19@imperial.ac.uk | github.com/ggwg | London, UK
                </h2>
              </span>
            </div>
            <div class="card-body">
              <div class="row px-3">
                <h2>Education</h2>
              </div>
              <div class="row px-3">
                <h3>Imperial College London &#183; 2019-2022</h3>
              </div>
              <div class="row px-3">Computer Science, BEng</div>
              <div class="row px-3">
                Modules: Software Engineering Design, Java, C, Algorithm
                Analysis, Databases, Hardware + Architecture, etc.
              </div>
              <br />
              <div class="row px-3">
                <h3>Caistor Grammar School &#183; 2012-2019</h3>
              </div>
              <div class="row px-3">
                A-Levels: A*A*A*A*A* - Further Maths, Maths, Physics, Biology,
                Extended Project
              </div>
              <div class="row px-3">GCSEs: 12 A*</div>
              <hr />
              <div class="row px-3">
                <h2>Achievements & Awards</h2>
              </div>
              <div class="row px-3">
                <h3>
                  <ul>
                    <li>Imperial College – University Entrance Scholarship</li>
                    <li>
                      1st Place – Best University Presentation &#183; 2020
                      <ul>
                        <li>
                          Delivered winning speech on “The Technology Behind
                          Amazon”
                        </li>
                      </ul>
                    </li>
                    <li>British Mathematical Olympiad &#183; 2019</li>
                    <li>
                      Senior Team Maths Challenge (National Finalist) &#183;
                      2018
                    </li>
                    <li>British Biology Olympiad (Gold Medal) &#183; 2019</li>
                  </ul>
                </h3>
              </div>
              <hr />
              <div class="row px-3">
                <h2>Projects & Experience</h2>
              </div>
              <div class="row px-3">
                <h3>
                  C Image Steganography & Encryption
                  <ul class="normal">
                    <li>
                      Collaborated with a team of 4 to develop a software
                      application in C, which can hide files inside the least
                      significant bits of each image pixel, without the use of
                      any external libraries.
                    </li>
                    <li>
                      Individually programmed the AES encryption algorithm – A
                      given password is hashed into an encryption key, which can
                      then be used to encrypt the binary file data to be encoded
                      inside the image
                    </li>
                  </ul>
                </h3>
              </div>
              <div class="row px-3">
                <h3>
                  Fortran Software Licensing – 8 week summer intern
                  <ul class="normal">
                    <li>
                      Designed & developed Windows software using Visual Studio.
                    </li>
                    <li>
                      Produced an in-house software licensing schema for a
                      turbomachinery consultancy company using Fortran, which
                      only allows a program to be run on a single computer,
                      within a limited time period.
                    </li>
                    <li>
                      Analyzed different encryption algorithms to decide on the
                      best trade-off between performance, difficulty of
                      implementation and ease of future maintenance.
                    </li>
                  </ul>
                </h3>
              </div>
              <div class="row px-3">
                <h3>
                  C ARM Assembler • GitHub on request
                  <ul class="normal">
                    <li>
                      Developed a program which converts ARM assembly language
                      into binary code, written in C.
                    </li>
                    <li>
                      Implemented a two-pass assembly, which stores memory
                      addresses of labels in the first pass, then converts the
                      instruction opcode and operand into binary.
                    </li>
                    <li>
                      Gained knowledge of bit-manipulation and a deeper
                      understanding of low level computer architecture.
                    </li>
                  </ul>
                </h3>
              </div>
              <div class="row px-3">
                <h3>
                  Imperial College Hackathon – Runners-Up (Newcomer’s Hack)
                  <ul class="normal">
                    <li>
                      Developed short-sightedness prevention app that monitors
                      proximity of eyes to screen using React Native, in the
                      UK’s largest student hackathon.
                    </li>
                  </ul>
                </h3>
              </div>
              <hr />
              <div class="row px-3">
                <h2>Technologies</h2>
              </div>
              <div class="row px-3">
                <h3>Proficient</h3>
              </div>
              <div class="row px-3">
                Python, Java, C, Scala, VueJS, CSS, HTML, Fortran, Git, Linux,
                Visual Studio (Windows)
              </div>
              <br />
              <div class="row px-3">
                <h3>Exposed to</h3>
              </div>
              <div class="row px-3">Javascript, Haskell, C#</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      icons: [
        { name: "ni ni-active-40" },
        { name: "ni ni-air-baloon" },
        { name: "ni ni-album-2" },
        { name: "ni ni-align-center" },
        { name: "ni ni-align-left-2" },
        { name: "ni ni-ambulance" },
        { name: "ni ni-app" },
        { name: "ni ni-archive-2" },
        { name: "ni ni-atom" },
        { name: "ni ni-badge" },
        { name: "ni ni-bag-17" },
        { name: "ni ni-basket" },
        { name: "ni ni-bell-55" },
        { name: "ni ni-bold-down" },
        { name: "ni ni-bold-left" },
        { name: "ni ni-bold-right" },
        { name: "ni ni-bold-up" },
        { name: "ni ni-bold" },
        { name: "ni ni-book-bookmark" },
        { name: "ni ni-books" },
        { name: "ni ni-box-2" },
        { name: "ni ni-briefcase-24" },
        { name: "ni ni-building" },
        { name: "ni ni-bulb-61" },
        { name: "ni ni-bullet-list-67" },
        { name: "ni ni-bus-front-12" },
        { name: "ni ni-button-pause" },
        { name: "ni ni-button-play" },
        { name: "ni ni-button-power" },
        { name: "ni ni-calendar-grid-58" },
        { name: "ni ni-camera-compact" },
        { name: "ni ni-caps-small" },
        { name: "ni ni-cart" },
        { name: "ni ni-chart-bar-32" },
        { name: "ni ni-chart-pie-35" },
        { name: "ni ni-chat-round" },
        { name: "ni ni-check-bold" },
        { name: "ni ni-circle-08" },
        { name: "ni ni-cloud-download-95" },
        { name: "ni ni-cloud-upload-96" },
        { name: "ni ni-compass-04" },
        { name: "ni ni-controller" },
        { name: "ni ni-credit-card" },
        { name: "ni ni-curved-next" },
        { name: "ni ni-delivery-fast" },
        { name: "ni ni-diamond" },
        { name: "ni ni-email-83" },
        { name: "ni ni-fat-add" },
        { name: "ni ni-fat-delete" },
        { name: "ni ni-fat-remove" },
        { name: "ni ni-favourite-28" },
        { name: "ni ni-folder-17" },
        { name: "ni ni-glasses-2" },
        { name: "ni ni-hat-3" },
        { name: "ni ni-headphones" },
        { name: "ni ni-html5" },
        { name: "ni ni-istanbul" },
        { name: "ni ni-key-25" },
        { name: "ni ni-laptop" },
        { name: "ni ni-like-2" },
        { name: "ni ni-lock-circle-open" },
        { name: "ni ni-map-big" },
        { name: "ni ni-mobile-button" },
        { name: "ni ni-money-coins" },
        { name: "ni ni-note-03" },
        { name: "ni ni-notification-70" },
        { name: "ni ni-palette" },
        { name: "ni ni-paper-diploma" },
        { name: "ni ni-pin-3" },
        { name: "ni ni-planet" },
        { name: "ni ni-ruler-pencil" },
        { name: "ni ni-satisfied" },
        { name: "ni ni-scissors" },
        { name: "ni ni-send" },
        { name: "ni ni-settings-gear-65" },
        { name: "ni ni-settings" },
        { name: "ni ni-single-02" },
        { name: "ni ni-single-copy-04" },
        { name: "ni ni-sound-wave" },
        { name: "ni ni-spaceship" },
        { name: "ni ni-square-pin" },
        { name: "ni ni-support-16" },
        { name: "ni ni-tablet-button" },
        { name: "ni ni-tag" },
        { name: "ni ni-tie-bow" },
        { name: "ni ni-time-alarm" },
        { name: "ni ni-trophy" },
        { name: "ni ni-tv-2" },
        { name: "ni ni-umbrella-13" },
        { name: "ni ni-user-run" },
        { name: "ni ni-vector" },
        { name: "ni ni-watch-time" },
        { name: "ni ni-world" },
        { name: "ni ni-zoom-split-in" },
        { name: "ni ni-collection" },
        { name: "ni ni-image" },
        { name: "ni ni-shop" },
        { name: "ni ni-ungroup" },
        { name: "ni ni-world-2" },
        { name: "ni ni-ui-04" },
      ],
    };
  },
  methods: {
    onCopy(el) {
      var test = document.getElementById(el);
      test.select();
      document.execCommand("copy");
    },
  },
};
</script>

<style>
.normal {
  font-weight: normal;
}
</style>
