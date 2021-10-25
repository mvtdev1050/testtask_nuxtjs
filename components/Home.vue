<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="z-0 bg-blue-50 py-16 curve-top">
      <h2
        class="text-5xl text-center p-4 font-medium text-gray-600 font-handwritten leading-tight"
      >
        Deine Job website
      </h2>
      <div class="">
        <img src="~/assets/images/undraw_agreement_aajr.png" />
      </div>
    </div>
    <div class="flex flex-wrap pt-8 pb-20">
      <div class="w-full">
        <ul class="flex mb-0 list-none flex-wrap pt-3 px-2 pb-4 flex-row">
          <li class="-mb-px mr-0 flex-auto text-center">
            <a
              class="
                text-xs
                font-bold
                border
                uppercase
                px-5
                py-3
                rounded-tl-xl rounded-bl-xl
                block
                leading-normal
              "
              v-on:click="toggleTabs(1)"
              v-bind:class="{
                'text-green-300 bg-white': openTab !== 1,
                'text-white bg-green-300': openTab === 1,
              }"
            >
              Arbeitnehmer
            </a>
          </li>
          <li class="-mb-px mr-0 flex-auto text-center">
            <a
              class="
                text-xs
                font-bold
                border
                uppercase
                px-5
                py-3
                block
                leading-normal
              "
              v-on:click="toggleTabs(2)"
              v-bind:class="{
                'text-green-300 bg-white': openTab !== 2,
                'text-white bg-green-300': openTab === 2,
              }"
            >
              Arbeitgeber
            </a>
          </li>
          <li class="-mb-px mr-0 flex-auto text-center">
            <a
              class="
                text-xs
                font-bold
                uppercase
                border
                px-5
                py-3
                rounded-br-xl rounded-tr-xl
                block
                leading-normal
              "
              v-on:click="toggleTabs(3)"
              v-bind:class="{
                'text-green-300 bg-white': openTab !== 3,
                'text-white bg-green-300': openTab === 3,
              }"
            >
              Temporärbüro
            </a>
          </li>
        </ul>
        <div
          class="
            relative
            flex flex-col
            min-w-0
            break-words
            w-full
            mb-6
            shadow-lg
            rounded
          "
        >
          <div class="py-5 flex-auto">
            <div class="tab-content tab-space">
              <div
                v-bind:class="{ hidden: openTab !== 1, block: openTab === 1 }"
              >
                <div>
                  <h4
                    class="
                      text-xl
                      font-medium
                      leading-6
                      text-center
                      px-12
                      text-gray-500
                    "
                  >
                    Drei einfache Schritte zu deinem neuen Job
                  </h4>
                  <div>
                    <div class="flex py-6 items-end relative">
                      <div
                        class="
                          w-52
                          absolute
                          rounded-full
                          top-20
                          -left-12
                          h-52
                          bg-gray-50
                          negative-index
                        "
                      ></div>
                      <span class="z-10 text-9xl text-gray-500 font-handwritten">1.</span>
                      <div class="z-10">
                        <img
                          src="~/assets/images/undraw_Profile_data_re_v81r.png"
                          alt=""
                        />
                        <h6 class="pt-12 mb-1 text-base text-gray-500 ml-4">
                          Erstellen dein Lebenslauf
                        </h6>
                      </div>
                    </div>
                    <div class="bg-blue-50 z-50 pb-12 curve-top">
                      <div class="flex py-6 items-end justify-center">
                        <span class="text-9xl text-gray-500 font-handwritten">2.</span>
                        <h6 class="mb-2 text-base text-gray-500 ml-4">
                          Erstellen dein Lebenslauf
                        </h6>
                      </div>
                      <div class="flex justify-center">
                        <img
                          src="~/assets/images/undraw_task_31wc.png"
                          alt=""
                        />
                      </div>
                    </div>
                    <div class="relative -top-8">
                      <div
                        class="
                          w-72
                          absolute
                          left-0
                          rounded-full
                          -left-16
                          h-72
                          bg-gray-50
                          negative-index
                        "
                      ></div>
                      <div class="flex pt-6 items-center z-10 justify-center">
                        <span class="text-9xl z-10 text-gray-500 font-handwritten">3.</span>
                        <h6 class="text-base text-gray-500 z-10">
                          Mit nur einem Klick bewerben
                        </h6>
                      </div>
                      <div class="flex justify-center z-10">
                        <img
                          src="~/assets/images/undraw_personal_file_222m.png"
                          alt=""
                          class="z-10"
                        />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                v-bind:class="{ hidden: openTab !== 2, block: openTab === 2 }"
              >
                <div>
                  <h4
                    class="
                      text-xl
                      font-medium
                      leading-6
                      text-center
                      px-12
                      text-gray-500
                    "
                  >
                    Drei einfache Schritte zu deinem neuen Mitarbeiter
                  </h4>
                  <div>
                    <div class="flex py-6 items-end relative">
                      <div
                        class="
                          w-52
                          absolute
                          rounded-full
                          top-20
                          -left-12
                          h-52
                          bg-gray-50
                          negative-index
                        "
                      ></div>
                      <span class="z-10 text-9xl font-handwritten text-gray-500">1.</span>
                      <div class="z-10">
                        <img
                          src="~/assets/images/undraw_Profile_data_re_v81r.png"
                          alt=""
                        />
                        <h6 class="pt-12 font-handwritten mb-1 text-base text-gray-500 ml-4">
                          Erstellen dein Lebenslauf
                        </h6>
                      </div>
                    </div>
                    <div class="bg-blue-50 z-50 pb-12 curve-top">
                      <div class="flex py-6 items-end justify-center">
                        <span class="text-9xl font-handwritten text-gray-500">2.</span>
                        <h6 class="mb-2 font-handwritten text-base text-gray-500 ml-4">
                          Erstellen ein Jobinserat
                        </h6>
                      </div>
                      <div class="flex justify-center">
                        <img
                          src="~/assets/images/undraw_about_me_wa29.png"
                          alt=""
                        />
                      </div>
                    </div>
                    <div class="relative -top-8">
                      <div
                        class="
                          w-72
                          absolute
                          left-0
                          rounded-full
                          -left-16
                          h-72
                          bg-gray-50
                        "
                      ></div>
                      <div class="flex pt-6 items-center z-10 justify-center px-12">
                        <span class="text-9xl z-10 font-handwritten text-gray-500">3.</span>
                        <h6 class="text-base text-gray-500 font-handwritten z-10">
                          Wähle deinen neuen Mitarbeiter aus
                        </h6>
                      </div>
                      <div class="flex justify-center z-10">
                        <img
                          src="~/assets/images/undraw_swipe_profiles1_i6mr.png"
                          alt=""
                          class="z-10"
                        />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                v-bind:class="{ hidden: openTab !== 3, block: openTab === 3 }"
              >
                <div>
                  <h4
                    class="
                      text-xl
                      font-medium
                      leading-6
                      text-center
                      px-12
                      text-gray-500
                       font-handwritten
                    "
                  >
                    Drei einfache Schritte zur Vermittlung neuer Mitarbeiter
                  </h4>
                  <div>
                    <div class="flex py-6 items-end relative">
                      <div
                        class="
                          w-52
                          absolute
                          rounded-full
                          top-20
                          -left-12
                          h-52
                          bg-gray-50
                          negative-index
                        "
                      ></div>
                      <span class="z-10 text-9xl text-gray-500  font-handwritten">1.</span>
                      <div class="z-10">
                        <img
                          src="~/assets/images/undraw_Profile_data_re_v81r.png"
                          alt=""
                        />
                        <h6 class="pt-12 mb-1 text-base font-handwritten text-gray-500 ml-4">
                          Erstellen dein Lebenslauf
                        </h6>
                      </div>
                    </div>
                    <div class="bg-blue-50 z-50 pb-12 curve-top">
                      <div class="flex py-6 items-end justify-center px-8">
                        <span class="text-9xl text-gray-500  font-handwritten">2.</span>
                        <h6 class="mb-2 text-base text-gray-500 font-handwritten ml-4">
                         Erhalte Vermittlungs- angebot von Arbeitgeber
                        </h6>
                      </div>
                      <div class="flex justify-center">
                        <img
                          src="~/assets/images/undraw_job_offers_kw5d.png"
                          alt=""
                        />
                      </div>
                    </div>
                    <div class="relative -top-8">
                      <div
                        class="
                          w-72
                          absolute
                          left-0
                          rounded-full
                          -left-16
                          h-72
                          bg-gray-50
                           font-handwritten
                        "
                      ></div>
                      <div class="flex pt-6 items-center z-10 justify-center px-12">
                        <span class="text-9xl z-10 text-gray-500 font-handwritten">3.</span>
                        <h6 class="text-base text-gray-500 font-handwritten z-10">
                          Vermittlung nach Provision oder Stundenlohn
                        </h6>
                      </div>
                      <div class="flex justify-center z-10">
                        <img
                          src="~/assets/images/undraw_business_deal_cpi9.png"
                          alt=""
                          class="z-10"
                        />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "pink-tabs",
  data() {
    return {
      openTab: 1,
    };
  },
  methods: {
    toggleTabs: function (tabNumber) {
      this.openTab = tabNumber;
    },
  },
};
</script>