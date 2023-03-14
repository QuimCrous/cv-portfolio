<template>
  <div>
    <!-- Start Projects Single Modal -->
    <div
      class="modal fade"
      :id="modal.modalId"
      tabindex="-1"
      aria-hidden="true"
    >
      <div
        class="modal-dialog modal-dialog-centered modal-dialog-scrollable modal-xl"
      >
        <div class="modal-content">
          <div class="modal-body">
            <div class="modal-header">
              <button
                type="button"
                class="btn-close"
                data-bs-dismiss="modal"
                aria-label="Close"
              ></button>
            </div>

            <div class="project-details-items">
              <div class="project-thumb">
                <img :src="modal.bigImgSrc" alt="Thumb" />
              </div>
              <div class="top-info">
                <div class="row">
                  <div class="col-xl-12 left-info">
                    <div class="project-info mt-md-50 mt-xs-40 mb-40">
                      <div class="content">
                        <ul class="project-basic-info">
                          <!-- <li>Client <span>validthemes</span></li> -->
                          <li>
                            Project Type <span>{{ modal.projectType }}</span>
                          </li>
                          <li>
                            Date <span>{{ modal.date }}</span>
                          </li>
                          <li>
                            Link
                            <span
                              ><a :href="modal.url" target="_blank">{{
                                modal.url
                              }}</a></span
                            >
                          </li>
                        </ul>
                        <!-- <ul class="social">
                          <li>
                            <h4>Share:</h4>
                          </li>
                          <li>
                            <a href="#"><i class="fab fa-facebook-f"></i></a>
                          </li>
                          <li>
                            <a href="#"><i class="fab fa-twitter"></i></a>
                          </li>
                          <li>
                            <a href="#"><i class="fab fa-linkedin-in"></i></a>
                          </li>
                          <li>
                            <a href="#"><i class="fab fa-pinterest-p"></i></a>
                          </li>
                        </ul> -->
                      </div>
                    </div>
                    <h2>{{ modal.title }}</h2>
                    <p>
                      {{ modal.description }}
                    </p>
                    <ul class="check-list mt-40">
                      <li>
                        <h4>{{ modal.checklist.titleOne }}</h4>
                        <p>
                          {{ modal.checklist.descriptionOne }}
                        </p>
                      </li>
                      <li>
                        <h4>{{ modal.checklist.titleTwo }}</h4>
                        <p>
                          {{ modal.checklist.descriptionTwo }}
                        </p>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>

              <div class="main-content mt-40">
                <p>
                  {{ modal.bigDescription }}
                </p>
                <div class="row">
                  <div class="col-lg-6 col-md-6">
                    <img :src="modal.smallImgSrcOne" alt="Thumb" />
                  </div>
                  <div class="col-lg-6 col-md-6">
                    <img :src="modal.smallImgSrcTwo" alt="Thumb" />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End Projects Single Modal -->
  </div>
</template>

<script setup>
import { ref, onUpdated, watchEffect, reactive } from "vue";
const props = defineProps({
  modal: Object,
});
</script>

<style lang="scss" scoped></style>
