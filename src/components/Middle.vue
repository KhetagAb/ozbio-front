<template>
  <div class="plan">
    <v-dialog
        v-model="dialog"
        hide-overlay
        width="50rem"
    >
      <template v-slot:activator="{ on }">
        <svg viewBox="0 0 24241.332 3386.6667">
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_Conserv"
                d="m 410.37888,363.02747 c 0,587.94667 -3.94595,591.89262 -3.94595,591.89262 H 1337.6773 V 359.08152 Z">
          </path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_Q3512"
                d="M 2444.7466,358.67277 V 960.5834 H 1393.4643 V 366.91812 h 1063.6503"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                d="M 325.69137,2003.6203 H 1306.8881 V 2960.081 H 321.56869 Z"></path>
          class="machine"
          id="m_Svarochniy"
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_PRESS"
                d="m 1467.6725,1999.4976 h 972.9514 v 964.7061 h -968.8287 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3A229"
                d="m 2770.438,519.45712 h 123.6802 v 65.9628 h 119.5576 l -6.4602,-24.10972 h 348.6423 l 15.317,26.52981 h 256.7796 V 816.28975 H 3252.791 v 57.71746 h -210.2565 v -53.59478 h -152.539 v 107.18956 h -123.6802 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3A227P"
                d="m 2892.3819,1544.8397 v -303.8382 h 193.3516 v -65.1082 h 195.3246 v 63.1353 h 157.838 v 211.1083 h -165.7299 l -7.1697,26.7579 h -168.4251 l 7.447,-27.7927 h -68.6093 v 97.7106 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3M227"
                d="m 3888.7345,467.59517 v 266.35168 h 252.5409 v 134.16233 h 503.1087 V 722.109 H 4543.7624 V 658.97378 H 4433.2757 V 467.59517 Z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3K228V"
                d="m 3908.4643,1096.9743 v 270.2977 h 252.5408 v 136.1353 h 501.1358 v -147.9732 h -98.6488 v -57.2163 h -112.4596 v -199.2705 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_TOYODA"
                d="m 2820.9009,1760.6216 v 479.9159 h 212.0558 v 41.8531 h 281.8111 v -44.6433 h 281.811 v -477.1257 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3A151"
                d="m 4056.9633,1830.3768 v 404.5803 h 200.895 v 41.8531 h 256.6992 v -36.2727 h 97.6573 v -89.2867 h 72.5454 v -83.7062 h -69.7552 v -186.944 h -281.8111 v -58.5944 h -279.0208 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3M132"
                d="m 4084.8653,2553.0408 h 945.8808 v 279.0209 h -239.958 v 153.4615 h -44.6433 l -22.3217,33.4825 -50.2237,-33.4825 h -83.7063 v 44.6433 h -259.4894 v -44.6433 h -248.3286 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3B722"
                d="m 2840.4323,2578.1527 h 744.9857 v 382.2586 h -332.0348 v 117.1888 h -86.4965 v -117.1888 h -326.4544 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_PTX"
                d="m 6685.3397,638.95776 h 770.0976 v 242.74815 h -770.0976 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_ARG"
                d="m 6685.3397,1196.9995 h 778.4682 v 231.5873 h -784.0486 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_ZEUS"
                d="m 6682.5495,1715.9783 h 784.0486 v 231.5873 h -778.4682 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_6R12_1"
                d="m 8803.108,1523.4539 217.6363,-186.944 -122.7692,-142.3006 153.4615,-119.979 117.1888,139.5104 53.0139,-39.0629 147.8811,175.7831 -44.6434,41.8532 128.3496,153.4614 -150.6712,122.7692 -128.3496,-145.0908 -220.4265,178.5733 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_6R8G_2"
                d="m 8194.8426,1640.6426 220.4265,-181.3635 -128.3496,-147.8811 150.6712,-131.1398 128.3496,147.8811 53.014,-36.2727 153.4614,178.5733 -53.0139,41.8531 122.7692,147.8811 -150.6713,119.979 -122.7692,-142.3007 -223.2167,184.1538 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_6R82G_3"
                d="m 7558.675,1668.5447 223.2167,-184.1537 -122.7692,-147.8811 147.8811,-119.979 c 0,0 108.8181,153.4615 119.979,147.8811 11.1608,-5.5804 55.8041,-41.8531 55.8041,-41.8531 l 145.0909,181.3635 -41.8532,39.0629 122.7692,153.4615 -147.881,119.979 -131.1398,-150.6713 -220.4265,181.3636 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_6R12_4"
                d="m 8007.8986,571.99276 189.7342,-153.46147 184.1537,214.84606 150.6713,-125.55939 125.5594,156.25168 -156.2517,122.76918 47.4336,47.43354 -184.1538,150.67127 -41.8531,-47.43355 -142.3007,117.18872 -125.5594,-145.09081 145.0909,-117.18876 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_6M13P_5"
                d="m 8747.3039,834.27236 145.0908,-125.55938 -181.3635,-217.63627 184.1537,-150.67126 175.7832,214.84606 156.2516,-125.55939 119.979,150.67126 -145.0908,119.97897 39.0629,55.80417 -178.5734,150.67127 -44.6433,-53.01397 -145.0908,122.76918 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_5A250P"
                d="m 7756.7798,2167.9921 h 357.1467 v 505.0277 h -359.9369 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1M63"
                d="m 8426.4299,2656.2786 290.1817,-792.4193 334.825,125.5594 -287.3915,792.4192 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1M63BD"
                d="m 9202.1079,2639.5373 398.9998,-1085.3911 376.6782,142.3006 -393.4195,1082.6009 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_5C276P"
                d="M 10485.604,1216.5309 V 560.83192 h 627.797 v 111.60835 h -145.091 v 546.88083 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_53A30"
                d="m 10530.247,1551.356 h 605.475 v 382.2585 h -608.265 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_5K310"
                d="m 10552.569,2209.8452 h 608.265 v 390.6292 h -608.265 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_5K32P"
                d="m 11272.443,1741.0901 h 474.335 v 831.4822 h -471.545 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_5140"
                d="m 11350.568,1261.1743 h 351.567 v 429.6921 h -357.147 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_Sborka"
                d="m 11950.463,577.57317 h 652.909 v 781.25843 h -652.909 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1"
                d="m 11953.254,1431.377 v 203.6852 h 259.489 v -206.4754 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_2"
                d="m 11953.254,1967.097 h 256.699 v 212.0559 h -259.49 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3"
                d="m 11953.254,2407.95 h 262.279 v 198.1048 h -267.86 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_4"
                d="m 12416.428,1428.5868 v 262.2796 h 206.476 v -265.0698 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_B"
                d="m 11950.463,2837.6421 v 209.2657 h 267.86 v -214.8461 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_7524PN"
                d="m 14173.855,2399.1381 h 1187.731 v 240.703 h -161.784 v 406.4329 h -410.378 v -418.2708 h -623.461 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_16K20"
                d="m 15488.448,1808.0552 h 717.083 v 50.2237 h 142.301 v 75.3356 h -136.72 v 131.1398 h -722.664 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_coord"
                d="m 15658.651,2477.7052 v 474.3355 h 474.335 v -468.7551 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1K62"
                d="m 17631.328,432.48233 h 206.475 v 231.58731 h 80.916 v 159.04189 h -78.125 v 231.58727 h -181.364 v -44.6433 h -25.112 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3_1"
                d="m 16958.888,2271.2298 h 147.881 v 50.2237 h 273.44 v -256.6992 h 186.944 v 234.3776 h 217.636 v -97.6573 h 237.168 v 97.6573 h 122.769 v 270.6502 h -770.097 V 2452.5933 H 17126.3 v 119.979 h -72.545 v -50.2238 h -92.077 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3_2"
                d="m 17377.419,1420.2162 h 767.307 v 510.6081 h -198.104 v -242.7481 h -220.427 v 92.0769 h -237.168 v -86.4965 h -114.398 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3_3"
                d="m 18549.307,585.9438 h 544.09 v 396.20962 h -544.09 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3_4"
                d="m 18462.81,1406.2651 h 764.517 v 267.86 l -11.11,-2.9771 v 117.3757 h -234.428 v -111.6083 h -524.559 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_3_5"
                d="m 18381.894,2262.8592 h 139.51 v 44.6433 h 276.231 v -262.2796 h 189.734 v 237.1677 h 217.637 v -86.4965 h 237.167 v 86.4965 h 111.609 v 273.4405 h -767.308 v -114.3986 h -242.748 v 114.3986 h -72.545 v -44.6434 h -97.658 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_2_1"
                d="m 19813.271,1344.8805 h 281.811 v 186.944 h -50.224 v 234.3775 h 108.819 v 150.6713 h -119.979 v 390.6292 h -69.756 v 58.5944 h -103.237 v -58.5944 h -276.231 v -212.0559 h 122.769 v -421.3215 h 97.657 v 94.8671 h 66.965 v -231.5873 h -58.594 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_2_2"
                d="m 19548.201,482.70608 h 505.028 v 189.73419 h -237.168 v 223.21668 h 106.028 v 234.37755 h -103.238 v 119.9789 h -270.65 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_2_3"
                d="m 20203.9,401.79003 h 212.056 v 114.39856 h 421.322 v 97.6573 h -97.658 v 72.54542 h 239.958 v -61.38459 h 184.154 v 281.81107 h -195.315 v -64.1748 h -228.797 v 125.55938 h -147.881 V 845.4332 h -393.419 v -72.54543 h -55.804 V 669.65006 h 53.014 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_2_4"
                d="m 20644.753,1922.4537 h 513.399 v -764.5171 h -270.651 v 119.9789 h -106.028 v 237.1678 h 108.819 v 223.2166 h -245.539 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_2_5"
                d="m 20053.229,2254.4885 h 142.301 v 47.4336 h 265.069 v -262.2796 h 192.525 v 245.5383 h 223.217 v -100.4475 h 239.957 v 97.6573 h 114.399 v 267.86 h -767.307 v -111.6083 h -248.329 v 119.979 h -69.755 v -55.8042 h -97.657 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1_1"
                d="m 21412.061,1855.4887 h 404.58 v 758.9367 h -404.58 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1_2"
                d="m 21414.851,906.81779 h 401.79 v 767.30731 h -407.371 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1_3"
                d="M 21389.739,471.54525 V 747.7759 h 385.049 V 471.54525 Z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1_4"
                d="m 22154.256,652.90881 h 136.72 v -97.6573 h 412.951 v 332.03482 h -136.72 V 1096.552 h 189.734 v 92.0769 h -189.734 v 401.79 h -189.734 v 58.5944 h 100.447 v 167.4125 h -217.636 v -161.8321 h 25.112 v -220.4265 h -119.979 v -139.5104 h 119.979 V 892.86674 h -131.14 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_1_5"
                d="m 21978.473,2285.1808 h 786.839 v 396.2096 h -786.839 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_MC032_1"
                d="m 22893.661,2151.2508 v -186.944 h 226.007 V 1484.391 h 103.238 v 89.2866 h 477.126 v 320.874 h -75.336 v 58.5944 h 119.979 v 78.1258 h -122.769 v 103.2378 h -237.168 l -5.07,18.9206 h -335.335 v -21.7109 h 72.545 v -53.0139 h -114.399 v 72.5454 z"></path>
          <path v-on="on"
                @click="selectMachine($event.target.id)"
                class="machine"
                id="m_MC032_2"
                d="M 22893.661,1141.1953 V 959.83175 h 228.797 V 477.12567 h 106.028 v 97.6573 h 477.126 v 318.08377 h -72.545 v 50.22376 h 117.188 v 72.5454 h -128.349 v 106.0279 h -234.378 v 27.9021 h -340.405 v -25.1118 h 69.755 v -50.2238 h -108.818 v 69.7552 z"></path>
        </svg>
        <img src="../assets/plan.png" style="max-width: 100%" alt="">
      </template>


      <v-card>
        <template slot="progress">
          <v-progress-linear
              color="deep-purple"
              height="10"
              indeterminate
          ></v-progress-linear>
        </template>

        <v-card-title>Управление станком</v-card-title>

        <v-card-text>
          <div>Изменяй.</div>
        </v-card-text>

        <v-card-title>Загруженность станка {{ selectedMachineId }}</v-card-title>

        <v-card-text>
          <v-data-table
              :headers="headers"
              :items="details"
              hide-default-footer
              class="table"
          >
            <template v-slot:item.progress="{ item }">
              <v-progress-linear
                  :value="100 * item.progress / (item.numOfDetails)"
                  height="30"
              >
                <strong>{{ item.progress  }} / {{ item.numOfDetails }}</strong>
              </v-progress-linear>

            </template>
          </v-data-table>
        </v-card-text>

        <v-card-actions>
          <v-btn
              class="ma-2"
              color="primary"
              dark
          >
            Сохранить
            <v-icon
                dark
                right
            >
              mdi-checkbox-marked-circle
            </v-icon>
          </v-btn>

          <v-btn
              class="ma-2"
              color="orange darken-2"
              dark
              @click="dialog = false"
          >
            <v-icon
                dark
                left
            >
              mdi-arrow-left
            </v-icon>Назад
          </v-btn>
        </v-card-actions>

      </v-card>
    </v-dialog>
  </div>
</template>

<script>
export default {
  name: "Middle",
  data: () => ({
    selectedMachineId: -1,
    dialog: false,
    headers: [
      {text: 'Наименование', value: 'name'},
      {text: 'Код', value: 'code'},
      {text: '№ операции', value: 'num'},
      {text: 'Прогресс', value: 'progress'},
      {text: 'Кол-во партии', value: 'numOfDetails'},
      {text: 'Время начала', value: 'startTime'},
      {text: 'Время окончания', value: 'endTime'},
    ],
    details: [
      {
        name: "Букса поворотная",
        code: "ПП54В.022",
        num: 1,
        progress: 210,
        numOfDetails: 300,
        startTime: "17.01.2022 14:00",
        endTime: "28.01.2022 9:30",
      },
    ],
  }),
  methods: {
    selectMachine(id) {
      this.selectedMachineId = id
    }
  }
}
</script>

<style scoped>
.plan {
  position: relative;
  text-align: center;
}

.machine {
  fill: #bf2523;
  opacity: .2;
}

.machine:hover {
  transition: opacity .2s ease;
  opacity: .5;
  cursor: pointer;
}

svg {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
}
</style>
